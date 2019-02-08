# Create Draft Article From Case

Use this Flow to add a Component or QuickAction that will add a Draft Article to a Case based on the Subject and Description of the Case.

Deloy in Summer '18 and later<br/>
<a href="http://bit.ly/createDraftArticleFromCase">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

If your Knowledge object has no Record Types<br/>
<a href="http://bit.ly/createDraftArticleFromCaseNoRecordTypes">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

<b>UPDATE: There seems to be an issue with the "Deploy to Salesforce" button.  That is currently being looked at by the creator, but in the meantime you can download this code locally as a ZIP and deploy from Workbench.  <a href="https://help.salesforce.com/articleView?id=000247614&language=en_US&type=1">More info here</a>
</b>

Prerequisites:
- Lighting Knowledge enabled
- Knowledge object with an API Name of Knowledge__kav
- Configure at least 1 Record Type on Knowledge__kav so that RecordTypeID field exists (if not using Record Types, install branch: norecordtypes)

To-Do:
- Currently this flow will display all Record Types to a user, even if she doesn't have access to create an article with that record type.  I want to add code that will determine which record types are available for the running user.

After Installation:
- Add the flow to the Case either as a Component or a QuickAction.  
- Customize which fields are pulled from the Case, displayed for editing, and written to the Article.
- Customize the Finish screen and any error message pages.
