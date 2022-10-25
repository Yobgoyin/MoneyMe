# MoneyMe Challenge
  
## Tools Used
- ASP.NET WEB API
- VUE 3 and Vite
- Docker
- MSSQL

## Related Submodules in the Project
- applicant_api - this is the web api for this project.
- loan_cli - front end project created in vue 3 and vite

## Prerequisite
- Docker

## Endpoints
- loan_cli - dev envi = localhost:5173
- applicant_api - docker = localhost:8081 |with swagger
- mssql - docker = localhost:8082

## Steps to Run the project
* Clone this project, and its related project
* Run Docker
* Go to the directory of this Project
* Make sure that all containers are running in Docker
* execute the following command
> docker-compose up --build
* Go to the directory of ths Project once again
* Traverse to loan_cli by using the command below
> cd loan_cli
* run the command below
> npm run dev

## Steps to explore the project
* go to localhost:8081
* add an applicant, upon creation it should return a url like below:
> localhost:5173/Home/{guid}
* enter this to your browser to be redirected on this page.
* Fill up the form and press Calculate Quote
* Check details and click Apply

## Blacklisted Numbers and Mobile
* Domains
> rocketmail and yahoo
* Mobile Numbers
> "09999999999", "09888888888", "09777777777"
