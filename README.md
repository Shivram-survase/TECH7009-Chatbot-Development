# TECH7009-Chatbot-Development
This contains all the files and code used to develop chatbot application for Oxford Brookes University

// Create a JavaScript file locally named BrookesBot_SnippetSettingsFile.js and upload to the Salesforce org as a static resource.

window._snapinsSnippetSettingsFile = (function() {

// Logs that the snippet settings file was loaded successfully
//console.log("Snippet settings file loaded.");

embedded_svc.snippetSettingsFile.extraPrechatFormDetails = [{
"label":"First Name",
"transcriptFields": ["FirstName__c"]
},{
"label":"Last Name",
"transcriptFields": ["LastName__c"]
},{
"label":"Email",
"transcriptFields": ["Email__c"]
}];
})();

