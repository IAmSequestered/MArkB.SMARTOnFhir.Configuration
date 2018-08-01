# MArkB.SMARTOnFhir.Configuration

This project is targeted at a .NET implimentation of SMART on FHIR. It demonstrates creating Configuration Groups in the Web/App.config files and reading those values into a Type. 

I've added a little bit that shows the user how to have multiple sections. Each of those groups pointing at different FHIR server and then selecting a different group with a single edit. This makes it so you don't have to try and keep track of several targets as you comment and un-commment several lines of settings in the .config file. This is shown in unit text CernerConfigGetAppClientId02 with the initialization of that in the TestInitialize method.

As a side benifit I've included a full Initialization section in the unit tests for those that haven't experienced those before. 
