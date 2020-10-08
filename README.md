# ⚡ Performance Engineering Questions

## ✨ Overview
As a performance tester/engineer, we have to understand of almost everything about the project, application and what not. To acquire that knowledge we need to ask questions to the architects, developers, product owners etc.

No questions are stupid, only the answers are. This repository will list out the questions you can ask to your team.

> *Even Einstein asked questions.*

## 🔍 Before you ask

Before you throw a lot of questions, I suggest you to do some ground work. Gather the details about the project, technical diagrams, internal documentations, also perform an internet search.

## ❗ Assumptions

- In this context, application means it could be a web application or services or database etc. Based on the project, you can ask the relevant questions.

## ❓ Questions

### 🕸 Application/Service

 - What is the objective of this exercise(performance testing)?
   - Infrastructure change
   - New app
   - User Interface change
   - Architecture change
 - Known performance issues
 - Can I get the access to the architecture diagram?
 - What is the core aspect of the application/service?
 - Tech stack of the application
 - Is the functional testing completed? 
 - Is the application served over HTTPS?
 - Is it Single Page Application?
 - Is the application on cloud?
   - On-premise
   - Off-premise
   - Hybrid
 - Is the auto scaling turned on?
 - Is caching enabled?
 - Is cookies needs to be handled?
 - Is CDN available?
 - Is the application load balanced?
 - Is the firewall enabled?
 - Is proxy required to access the application?
   - Reverse Proxy Settings
   - Forward Proxy Settings
 - Is the application dockerized?
 - How authentication works?
 - What is the container orchestration tool?
   - Kubernetes
   - Docker Swarm   
   - ...

### 🌐 Environment

 - Is it already available in production?
    - If it is in production, can I get access to the production logs?
 - Is stage or non-production environment available?
 - Is the test environment identical to the production?
    - If not, what is the scaled down factor?
 - Is APM solution available?
 - Is the performance testing environment up-to-date?
 - Is the application under test stable?
 - Do I get access to start/stop/restart the servers?
 - Is any service virtualized?
 - Is there any billing involved for any sort of services or environments?

### 👨‍👩‍👧‍👦 End Users

 - Who are all the end users?
 - End users' demographics
 - End users' device preferences
 - End users' network preferences
 - End users' browser preferences

### 🔢 SLAs, SLOs and all about numbers

 - What are all the SLAs and SLOs?
 - How many users/transactions need to be injected?
 - What is the throughput to achieve?
   - The context of throughput varies based on the tool you are working.
   - E.g. it could be number of successful orders per minute or the data (in bytes) transferred between the client and the server
 - Acceptable SLAs: 
    - Response time
    - Throughput
    - CPU
    - Memory
    - Garbage Collection
    - Disk
    - Network
 - What is the network virtualization distribution?
 - In case of containers, what could be the acceptable performance metrics at pod/cluster level?
 - What is the acceptable % of failures?
 - Do we have any in-house or industry benchmarks to compare?
 - Do we have any baseline test stats?

### 💾 Test Data

 - Is the test data available?
 - Is the test data reusable?
 - Is there a dedicated team available to help me out to generate test data?

### ⚒️ Tools

 - Is the performance testing tool available?
 - Is the relevant licenses available?
 - Do we need to inform any other team before we begin the testing?

### 📜 Scripting

 - Critical scenarios to be tested
 - List of browsers to be tested 
 - List of services and its method to be tested

### 📊 Testing

 - Types of performance testing in scope
 - Is the workload model design available?
 - Is IP spoofing required?
 - Ramp up, steady state, and ramp down duration
 - Duration of the test
 - Is baseline results available?
 - Is performance trend report required?
 - Is client-side metrics required?
 - Is background noise script required?
 
### 🔁 Process 

 - Before we start the test, do we need to inform any other team?
 - Timeline for the project
 - To whom I can assign the defect?
 - What is the escalation process?
 - What are all the risks involved in this project and its mitigation plan?
 - List of contacts of developers, architects, and others
 
### 💹 Stats

 - To whom I should share the report?
 - Do I need to share it daily or weekly?
 - Following are the metrics which will be available in the report.   
   * Minimum response time (ms)
   * Maximum response time (ms)
   * 90th percentile
   * Standard Deviation
   * Histogram
   * Hits per second
   * Number of transactions passed
   * Number of transactions failed
   * Throughput
   * Bytes Sent/Received
   * CPU utilization
   * Memory utilization
   * Garbage Collection

## After asking a question

Once you got the answers, make sure you record it. I use Microsoft OneNote to store all the project related knowledge. You could use a simple notepad with the timestamp or your favorite note-taking app. Make sure you are not violating company/client policy.

Every company has some sort of knowledge management process, you can follow them too.

## 🙏 Contributions

All kinds of contributions are welcome. Please submit a [PR](https://github.com/QAInsights/Performance-Engineering-Questions/pulls).
