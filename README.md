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


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.


## Scripts SQL for Introduce Data

- `CAPSRV_SALESHISTORYTYPE`

INSERT INTO CAPSRV_SALESHISTORYTYPE(ID, creationMonthAsDate, creationMonth, creationMonth_Text, grossAmountInCompanyCurrency, companyCurrency, companyCurrency_Text, referenceAmount) VALUES('22566921-7d57-4e76-bl4c-e53fd97dcbl4', '2020-05-31T12:15:00', '02', 'February', 655056.56, 'USD', 'United States Dollar', 200);
INSERT INTO CAPSRV_SALESHISTORYTYPE(ID, creationMonthAsDate, creationMonth, creationMonth_Text, grossAmountInCompanyCurrency, companyCurrency, companyCurrency_Text, referenceAmount) VALUES('21066921-7d57-4e76-bl4c-e53fd97dcbll', '2020-06-30T12:15:00', '04', 'April', 509008.45, 'USD', 'United States Dollar', 200);
INSERT INTO CAPSRV_SALESHISTORYTYPE(ID, creationMonthAsDate, creationMonth, creationMonth_Text, grossAmountInCompanyCurrency, companyCurrency, companyCurrency_Text, referenceAmount) VALUES('24466921-7d57-4e76-bl4c-e53fd97dcbl9', '2020-04-30T12:15:00', '03', 'March', 301360.41, 'USD', 'United States Dollar', 200);

