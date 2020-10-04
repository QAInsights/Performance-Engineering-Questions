# Performance Engineering Questions

## Overview
As a performance tester/engineer, we have to understand of almost everything about the project, application and what not. To acquire that knowledge we need to ask questions to the architects, developers, product owners etc.

No questions are stupid, only the answers are. This repository will list out the questions you can ask to your team.

*Even Einstein asked questions.*

## Questions
### Application/Service
 - What is the objective of this exercise(performance testing)?
 - Tech stack of the application
 - Is the functional testing completed?

### Environment

 - Is it already available in production?
 - If it is in production, can I get access to the production logs?
 - Is stage or non-production environment available?
 - Is the test environment identical to the production?
 - Is APM solution available?
 - Is the performance testing environment up-to-date?
 - Is the application under test stable?

### End Users

 - Who are all the end users?
 - End users demographics
 - End users device preferences.
 - End users network preferences.

### SLAs, SLOs and all about numbers

 - What are all the SLAs and SLOs?
 -  How many users/transactions need to be injected?
 - Acceptable SLAs: 
	 - Response time
	 - Throughput
	 - CPU
	 - Memory
	 - Garbage Collection
	 - Disk
	 - Network

### Test data

 - Is the test data available?
 - Is the test data reusable?
 - Is there a dedicated team available to help me out to generate test data?

### Tools

 - Is the performance testing tool available?
 - Is the relevant licenses available?

### Scripting

 - Critical scenarios to be tested
 - List of browsers to be tested 
 - List of services and its method to be tested

### Testing

 - Types of performance testing in scope
 - Is the workload model design available?
 
### Process 
 - Before we start the test, do we need to inform any other team?
 - Timeline for the project
 - To whom I can assign the defect?
 - What are all the risks involved in this project and its mitigation plan?
