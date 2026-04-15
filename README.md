# salesforce-github-actions

automatically pulls your metadata into github master so your admins can update flows and you will always see it in the history

### setup

copy the .github folder to a sfdx project and set your SFDX_AUTH_URL_PROD env var in github actions to the value from `sf org display --verbose --json`


