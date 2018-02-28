err-jira
=========

An errbot plugin for working with Atlassian JIRA.

OAuth for JIRA
----

Follow the guides on the JIRA developer pages:

- [Allowing oauth access](https://confluence.atlassian.com/jira/allowing-oauth-access-200213098.html "")
- [JIRA Rest APIs](https://developer.atlassian.com/jiradev/jira-apis/jira-rest-apis/jira-rest-api-tutorials/jira-rest-api-example-oauth-authentication "")
- [JIRA oauth python example](https://bitbucket.org/atlassian_tutorial/atlassian-oauth-examples/src/d625161454d1ca97b4515c6147b093fac9a68f7e/python/?at=default "")


Requirements
----

    pip install -r requirements.txt

- [jira](https://github.com/pycontribs/jira "jira")


Installation
----
    plugin will try to find API_URL, USERNAME and PASSWORD as an env.variables JIRA_URL, JIRA_USERNAME, JIRA_PASSWORD
    /repos install https://github.com/Grizzlyt/errbot-jira.git
    /plugin config Jira {'API_URL': 'http://jira.example.com', 'USERNAME': 'errbot', 'PASSWORD': 'password', 'PROJECTS': ['FOO', 'BAR']}
    /plugin activate Jira
