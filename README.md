# Postman-Newman Framework with GitHub Actions, Slack Reporting, HTML & Allure Reporting for GitHub API's

A E2E framework designed to test GitHub API's leveraging Postman, Newman with GitHub Actions integration along with Slack Reporting, Allure and HTML Extra reports.

![Postman Framework](https://github.com/doradlarajesh/GitHubPostManAPITesting/assets/57953464/f90ff7bd-e4bd-4fde-a630-3a191178c559)

# Aim
Github provides various API's to interact and get various information like users, repositories, branches, commits, actions, billing, commits. Our aim is to pick some of these Rest API's and test them with Postman, run them on a CICD platform like GitHub Actions with the help of Newman a CLI tool to execute postman tests, send those execution reports to Slack and create awesome looking HTML reports with the help of HTMLExtra and Allure Reports.

## GITHUB Rest API's and Assertions

Below Rest API's of GITHUB are tested in above framework
 - Get Repositories of a User
 - Create a Public Repo for User
 - Deleting a Repo

Below types of assertions are done for above API's they include both positive and negative scenarios.

 - Validating Status Code.
 - Validating Header information.
 - Validating Cookies information.
 - Validating Response Schema of Response.
 - Validating Response fields of Response based on different scenarios.


## Dependencies

With GitHub actions already integrated we can run directly from actions tab. Dependencies are only required if this collection needs to be run locally.

 - Node JS
 - Newman
 - Newman HTMLExtra
 - Newman Slack Reporter
 - Allure Report


Intro: Saying what exactly we are testing!!!
Assertions: DIfferent Assertions we are testing and Postive and Negative Scenarios
Mention about collection variables generated on the fly 
Monitor Capability
Reports Integration
Sample Report Snapshot
Create some Data file and get the data from that file like CSV
Running collection with Newman Integration
Probably GITHUB Actions Integration
Probably Docker Integration
