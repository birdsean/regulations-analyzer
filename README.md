# Regulations Analyzer

## Tasks
- [x] Write code to download the current eCFR
- [x] Analyze it for items such as word count per agency and historical changes over time
- [x] Add your own custom metrics
- [x] There should be a front end visualization for the content where we can click around and ideally query items
- [x] There should be a public github project with the code

## Demo

**Update 22 Feb 2025**: Hosting was too expensive so I tore the demo infrastructure down. Please email if you'd like to see it live. Here's some screenshots:

### Screenshots

![Image](https://github.com/user-attachments/assets/383aefb7-745e-4e5f-afda-e6eb4db85028)
![Image](https://github.com/user-attachments/assets/bf09b3ca-b8c9-4216-b5de-8ced242cffb3)
![Image](https://github.com/user-attachments/assets/a387d6dc-98f1-4152-b206-6d184fdfe0f0)

~~URL: http://k8s-superset-superset-acd1ac03e7-863469020.us-east-1.elb.amazonaws.com/superset/dashboard/1~~
~~Query Interface: http://k8s-superset-superset-acd1ac03e7-863469020.us-east-1.elb.amazonaws.com/sqllab/~~

~~- Username: admin~~
~~- Password: admin~~

### Notes
- Serves over http, so you'll need to "proceed anyway" on the browser security warning
- Runs on a serverless DB that will likely go cold so first load might take a minute or require a refresh if the request times out. Subsequent loads will be fast.

## Timelog
- 11 Feb: 4 hrs - First ETL and Superset prototype
- 12 Feb: 3 hrs - Rest of "level 0" ETLs and Superset progress
- 13 Feb: 7 hrs - Level 1-3 ETLs, Supserset on EKS, build metrics
- 14 Feb: 1 hrs - Final metrics, bugs, light cleanup
