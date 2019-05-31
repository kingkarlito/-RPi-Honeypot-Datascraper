# RPi Honeypot Datascraper

build webapp and website to display analysis of the data recorded by my own raspberry pi dshield honeypot


**Initial Design Plan** May 30, 2019

create RPi Dshield honeypot, guide @ https://isc.sans.edu/honeypot.html
Scrape my personal RPi honeypot's data from https://secure.dshield.org/dashboard.html not just using the data files automatically generated for submission to ISC
Use panda, similar like R maybe? to read and format data for
build sql database and begin analysis
graph the frequency of attacks / day and other interesting visual infographics
publish this analysis to my website
build android app that connects to database and generates analysis
set up email service to send daily reports
