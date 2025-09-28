## Singidunum University 

## AAI

## Cloud Computing and Software Development

## lab_Available_Flights_CC_SD_2025

Source code of the "Available Flights" web application developed during the Cloud Computing and Software Development course on AAI program on Singidunum University.

This application was used in software development lab to learn deployment process.

## Deployment

Example deployment script
```bash
#!/bin/bash
cd /tmp
rm -rf cloud-computing-and-software-development-2025
git clone https://github.com/pkresoja/cloud-computing-and-software-development-2025

cd cloud-computing-and-software-development-2025
rm -rf /var/www/html/*
mv ./src/* /var/www/html

echo 'Done :)'
```
29.9.2025.