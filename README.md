# Create Draft Article From Case

Use this Flow to add a Component or QuickAction that will add a Draft Article to a Case based on the Subject and Description of the Case.

<a href="https://githubsfdeploy.herokuapp.com?owner=derekdanderson&repo=createdraftarticlefromcase">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

Prerequisites:
- Lighting Knowledge enabled
- Knowledge object with an API Name of Knowledge__kav
- Configure at least 1 Record Type on Knowledge__kav so that RecordTypeID field exists

To-Do:
- Currently this flow will display all Record Types to a user, even if she doesn't have access to create an article with that record type.  I want to add code that will determine which record types are available for the running user.

