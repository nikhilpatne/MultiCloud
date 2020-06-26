# MultiCloud
Repository contains ansible role which will provision virtual machine on all cloud providers

<Agent/Component Name> - Linux Playbook
============================================================
This Component provides automation to deploy, configure and control the  xxxx agent

Product Information
--------------------
Product: <Agent/Component Name> - Linux

Vendor: <Vendor name>

Vendor Site: <vendor site>

Version Supported: <version supported>

Requirements
------------

Tested Operating Systems

- RHEL on 7.6


Operating System Pre-Requisites

  <prereqs as per applicable for agent/component>

	  
Dependencies
------------

<Any other dependencies of playbook/roles>


Role Variables
--------------

## Tasks

<List of tasks and their short descripton>



Playbook defaults and variables

| Variable Name   | Variable Description   |  Example Value of Variable |
| :---------------| :----------------------| :--------------------------|
| {{temp_dir}}  | An absolute path to a directory that will be used to hold any temporary files created as part of the automation  |  '/tmp'         | (just example)




Example Playbook
----------------

The below example playbook shows how to install <agent/component > specifying some infrastructure dependent parameters:

    - hosts: <hosts>
      roles:
         - { role: <role_name>, <extra_params_list> }

License
-------
License and Maintainer

Maintainer: <code maintainer>

License: <license info>
