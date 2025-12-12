# Link to GitHub repository

<!-- Provide a link to the plugin or component repository you want to modify -->

List the GitHub usernames of the users who should have commit permissions below:
- `@username1`
- `@username2`

This is needed in order to cut releases of the plugin or component.

If you are modifying the release permission of your plugin or component, fill out the following checklist:

<!-- If you're enabling CD only, leave the following checklist blank! -->

### Release permission checklist (for submitters)

- [ ] The usernames of the users added to the "developers" section in the .yml file are the same the users use to log in to [accounts.jenkins.io](https://accounts.jenkins.io/).
- [ ] All users added have logged in to [Artifactory](https://repo.jenkins-ci.org/) and [Jira](https://issues.jenkins.io/) once.
- [ ] I have mentioned an [existing team member](https://github.com/orgs/jenkinsci/teams) of the plugin or component team to approve this request.


### Reviewer checklist

- [ ] Check that the `$pluginId Developers` team has `Admin` permissions while granting the access.
- [ ] In the case of plugin adoption, ensure that the Jenkins Jira default assignee is either removed or changed to the new maintainer.
- [ ] If security contacts are changed (this includes add/remove), ping the security officer (currently `@Wadeck`) in this pull request. If an email contact is changed, wait for approval from the security officer.
