## API Testing Report

#### [Booking - API Testing Report](https://api-testing-report1-sakib.netlify.app/)
#### [Student Details - API Testing Report](https://api-testing-report2-sakib.netlify.app/)

## Method
- POST
- GET
- PUT
- DELETE

## Command

1) **Newman Install Command:**
   - npm install -g newman

2) **Report Install Command:**
   - npm install -g newman-reporter-html
   - npm install -g newman-reporter-htmlextra

3) **Report Run Command:**
   - newman run CollectionName.json -e EnvironmentName.json
   - newman run CollectionName.json -e EnvironmentName.json -r cli,html
   - newman run CollectionName.json -e EnvironmentName.json -r cli,htmlextra 
   - newman run CollectionName.json -e EnvironmentName.json -r cli,htmlextra --insecure
