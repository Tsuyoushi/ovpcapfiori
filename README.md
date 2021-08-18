# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Scripts SQL for Introduce Data

`CAPSRV_SALESHISTORYTYPE`

- INSERT INTO CAPSRV_SALESHISTORYTYPE(ID, creationMonthAsDate, creationMonth, creationMonth_Text, grossAmountInCompanyCurrency, companyCurrency, companyCurrency_Text, referenceAmount) VALUES('22566921-7d57-4e76-bl4c-e53fd97dcbl4', '2020-05-31T12:15:00', '02', 'February', 655056.56, 'USD', 'United States Dollar', 200);

- INSERT INTO CAPSRV_SALESHISTORYTYPE(ID, creationMonthAsDate, creationMonth, creationMonth_Text, grossAmountInCompanyCurrency, companyCurrency, companyCurrency_Text, referenceAmount) VALUES('21066921-7d57-4e76-bl4c-e53fd97dcbll', '2020-06-30T12:15:00', '04', 'April', 509008.45, 'USD', 'United States Dollar', 200);

- INSERT INTO CAPSRV_SALESHISTORYTYPE(ID, creationMonthAsDate, creationMonth, creationMonth_Text, grossAmountInCompanyCurrency, companyCurrency, companyCurrency_Text, referenceAmount) VALUES('24466921-7d57-4e76-bl4c-e53fd97dcbl9', '2020-04-30T12:15:00', '03', 'March', 301360.41, 'USD', 'United States Dollar', 200);

`CAPSRV_SALESPERSUPPLIERTYPE`

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-bl4c-e53fd97dcbl2', '100000036', 'African Gold And Diamond Corporation','2722.24','81.70',28,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-bl4c-e53fd97dcbll','100000029','C.R.T.U.','23685.76','169.35',101,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-bl4c-e53fd97dcb09','100000037','PicoBit','5298.80','101.20',44,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('19466921-7d57-4e76-bl4c-e53fd97dcbl2','100000008','AVANTEL','8042.02','71.29',77,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20226921-7d57-4e76-bl4c-e53fd97dcbl2','100000001','Becker Berlin','910.35','45.00',17,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-b24c-e53fd97dcbl2','100000007','Laurent','20066.97','168.45',107,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d58-4e76-bl4c-e53fd97dcbl2','100000016','Mexican Oil Trading Company','37866.99','705.06',63,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466911-7d57-4e76-b24c-e53fd97dcbl2','100000044','Sorali','742.56','39.00',16,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-bl4c-e83fd97dcbl2','100000000','SAP','60294.92','956.00',53,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-al4c-e53fd97dcbl2','100000030','Jologa','62304.83','382.59',143,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7f57-4e76-bl4c-e53fd97dcbl2','100000019','Pateu','19481.49','236.56',79,'USD','EA','US Dollar');

- INSERT INTO CAPSRV_SALESPERSUPPLIERTYPE(ID,supplier,supplierName,grossAmountInCompanyCurrency,netUnitPriceInCompanyCurrency,quantity,companyCurrency,quantityUnit,companyCurrencyShortName) VALUES ('20466921-7d57-4e76-bl4c-e53fd87dcbl2','100000038','Bionic Research Lab','4664.44','139.99',28,'USD','EA','US Dollar');


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
