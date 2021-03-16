# Datastore 

## Create Datastore 

### SQL Database

|property|value|
|-|-|
|IP|mtcsdevsqlsrv.database.windows.net|
|ID|sqladmin|
|PW||
|Query|SELECT *	FROM [SalesLT].[SalesOrderHeader] join [SalesLT].[SalesOrderDetail] 	    ON SalesOrderHeader.SalesOrderID = SalesOrderDetail.SalesOrderID|



## Create Dataset 

### From URL

|Property|value|
|-|-|
|URL|https://github.com/xlegend1024/az-cloudscale-adv-analytics/blob/master/sampledata/customerchurnsource.csv?raw=true|