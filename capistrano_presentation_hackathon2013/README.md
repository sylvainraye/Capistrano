Capistrano Presentation
=======================

Author: Sylvain Rayé<br>
Date: 10 March 2013<br>
Event: Mage Hackathon Zürich

## Description

Deploy a project like Magento thanks to a web application deployment framework, Capistrano.

- Description
- Installation and use
- Configuration and creation of own tasks
- Work with multi stages
- Magentify (Capistrano extensions which add some tasks for Magento Projects)
- Demos and code to help you to start by yourself

## Some requirements for the demos

- You will find here all the code used during the demos into the presentation.
In the demo, the requirements were to create two virtual hosts on a virtual machine, one for the staging (staging.magehackathon.local) and one for the production (production.magehackathon.local).
- An access via SSH is mandatory on the remote server(s) with same user and password on all servers.
- For demo purpose the git repository was local but you can change the git repository url and version control variables for Capistrano to take a git repository on a remote server or you can even change the version control type, its branch or even the strategy to deploy the code. See variable ':deploy_via'

## Author

* Sylvain Rayé
* http://www.sylvainraye.com/
* [@sylvainraye](https://twitter.com/sylvainraye)
* [Follow me on github!](https://github.com/diglin)
