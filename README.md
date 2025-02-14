# Regulations Analyzer

## Tasks
- [x] Write code to download the current eCFR
- [x] Analyze it for items such as word count per agency and historical changes over time
- [x] Add your own custom metrics
- [x] There should be a front end visualization for the content where we can click around and ideally query items
- [x] There should be a public github project with the code

## Demo
URL: http://k8s-superset-superset-acd1ac03e7-863469020.us-east-1.elb.amazonaws.com/superset/dashboard/1
Query Interface: http://k8s-superset-superset-acd1ac03e7-863469020.us-east-1.elb.amazonaws.com/sqllab/

Username: admin
Password: admin

### Notes
- Serves over http, so you'll need to "proceed anyway" on the browser security warning
- Runs on a serverless DB that will likely go cold so first load might take a minute or require a refresh if the request times out. Subsequent loads will be fast.

## Timelog
11 Feb: 4 hrs - First ETL and Superset prototype
12 Feb: 3 hrs - Rest of "level 0" ETLs and Superset progress
13 Feb: 7 hrs - Level 1-3 ETLs, Supserset on EKS, build metrics
14 Feb: 1 hrs - Final metrics, bugs, light cleanup
