# Create Draft Article From Case

Use this Flow to add a Component or QuickAction that will add a Draft Article to a Case based on the Subject and Description of the Case.

If your Knowledge object has no Record Types<br/>
<a href="http://bit.ly/createDraftArticleFromCaseNoRecordTypes">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

Prerequisites:
- Lighting Knowledge enabled
- Knowledge object with an API Name of Knowledge__kav

To-Do:
- Currently this flow will display all Record Types to a user, even if she doesn't have access to create an article with that record type.  I want to add code that will determine which record types are available for the running user.

After Installation:
- Add the flow to the Case either as a Component or a QuickAction.  
- Customize which fields are pulled from the Case, displayed for editing, and written to the Article.
- Customize the Finish screen and any error message pages.
