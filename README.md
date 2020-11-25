# TradeAppBackend-NodeJS-MYSQL-Express
Backend Assignment

Nodejs - MySQL (MariaDB) - Sequelize - Express 


=>  run 'npm install' for node modules

=>  run 'node index.js' or run 'npm start'


# Methods	-  Urls	-		Actions

* (shareholder.route.js)


GET	      api/shareholders get all Shareholders

GET	      api/shareholders/:id	get Shareholder by id

GET	      api/shareholders/portfolio/:id	get Shareholder portfolio by shareholder id

PUT	      api/shareholders/:id	update Shareholder by id

DELETE	  api/shareholders/:id	remove Shareholder by id


* (share.route.js)


GET	      api/shares		get all Shares

GET	      api/shares/:id		get Share by id

PUT	      api/shares/:id		update Share by id

DELETE	  api/shares/:id		remove Share by id

POST	    api/shares/buyshare/:id/:share_name/:count/:rate	buy share

POST	    api/shares/sellshare/:id/:share_name/:count/:rate	sell share


* (portfolio.route.js)


GET	      api/portfolios		get all Portfolios

GET	      api/portfolios/:id	get Portfolio by id

PUT	      api/portfolios/:id	update Portfolio by id

DELETE	  api/portfolios/:id	remove Portfolio by id
