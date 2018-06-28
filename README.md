Update: June 2018 moved to [Gitlab](https://gitlab.com/eschabell/bpms-anti-money-laundering-demo)


JBoss BPM Suite Anti Money Laundering Demo
==========================================
Demo based on JBoss BPM Suite and JBoss Data Grid products showcasing an anti money laundering warning system
using rules, events, data grid and processes.


Install on your machine
-----------------------
1. [Download and unzip.](https://github.com/eschabell/bpms-anti-money-laundering-demo/archive/master.zip)

2. Add products to installs directory.

3. Run 'init.sh' file.

4. Start the JBoss Data Grid sever with port offset, -Djboss.socket.binding.port-offset=100.

5. Start the JBoss BPM Suite server, login, build and deploy JBoss BPM Suite process project at http://localhost:8080/business-central (u:erics/p:bpmsuite1!).

6. Enjoy the demo!


TODO: Running an instance that triggers money laundering warning in system.
---------------------------------------------------------------------
1. Build & deploy project.

2. Start process with following data in start form (either from JBoss BPM Suite dashboard or using external client
	 UI deployed at [http://localhost:8080/external-client-ui-form-1.0](http://localhost:8080/external-client-ui-form-1.0)):

  ```
  TODO: add data here.
  ```

3. Login to [http://localhost:8080/business-central](http://localhost:8080/business-central)

  ```
  - login for admin role (u:erics / p:bpmsuite1!)
  ```

4. TODO: add all steps needed here.


Supporting Articles
-------------------
- [7 Steps to Your First Process with JBoss BPM Suite Starter	Kit](http://www.schabell.org/2015/08/7-steps-first-process-jboss-bpmsuite-starter-kit.html)


Released versions
-----------------
See the tagged releases for the following versions of the product:

- v1.0 - JBoss BPM Suite 6.1 and JBoss Data Grid 6.5.1 with anti money laundering application installed.

![BPM Suite BAM](https://raw.githubusercontent.com/eschabell/bpms-anti-money-laundering-demo/master/docs/demo-images/mock-bpm-data.png?raw=true)

