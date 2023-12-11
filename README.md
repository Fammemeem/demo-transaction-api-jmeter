# demo-transaction-api-jmeter

## Prerequisite:
- Apache JMeter

## About this project:
This is a demo fintech transaction API project. There are some users like Agent, Customer, Merchant. The agent can deposit. Customer can check balance, withdraw and payment to merchant. Here I have chained multiple API's using JMeter and generated report using CLI. 

## How to run this project:
- Clone this project
  ``` https://github.com/Fammemeem/demo-transaction-api-jmeter ```
- Open the given jmx file in Apache JMeter
- Goto View Results Tree & click on run button

## How to generate CLI report:
- First, create a folder
- Copy the jmx file & paste the jmx file in that folder
- Goto terminal and give following command
  ``` jmeter -n -t .\RandomUserAPI.jmx -l .\RandomUserAPI.csv -e -o Reports ```
