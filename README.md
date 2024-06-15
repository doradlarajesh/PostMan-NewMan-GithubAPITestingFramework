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

![postman snapshot](https://github.com/doradlarajesh/GitHubPostManAPITesting/assets/57953464/760faeb8-bc65-4247-8d30-656fe3833449)

## Dependencies

With GitHub actions already integrated we can run directly from actions tab. Dependencies are only required if this collection needs to be run locally.

 - Node JS
 - Newman
 - Newman HTMLExtra
 - Newman Slack Reporter
 - Allure Report

![githubactions1](https://github.com/doradlarajesh/GitHubPostManAPITesting/assets/57953464/65e08468-79b1-4b6b-9012-55d48ecd7d28)

## Slack Report
![slack report](https://github.com/doradlarajesh/GitHubPostManAPITesting/assets/57953464/84941545-e5cf-4dee-a613-027b23023c07)

## HTML Report
![Html report1](https://github.com/doradlarajesh/GitHubPostManAPITesting/assets/57953464/d839f458-ff17-45fc-aab0-702ca4289de9)
![HTML Report2](https://github.com/doradlarajesh/GitHubPostManAPITesting/assets/57953464/13a47f6e-bbe2-421c-902c-73db01f88e21)

## Allure Report
![Screenshot 2024-06-15 154638](https://github.com/doradlarajesh/PostMan-NewMan-GithubAPITestingFramework/assets/57953464/d0df7de9-aa31-4f9e-b6b0-a9e6aed4bf8a)




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
