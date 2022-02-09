# Ansible Collection - middleware_automation.wildfly

[![Build Status](https://github.com/ansible-middleware/wildfly/workflows/CI/badge.svg?branch=master)](https://github.com/ansible-middleware/wildfly/actions/workflows/ci.yml)

## About

This Ansible Collection regroups several playbooks (packaged as role) to help install, setup and maintain Java JEE appserver Wildfly (and its product counterpart  [JBoss Enterprise Application (EAP)](https://www.redhat.com/en/technologies/jboss-middleware/application-platform) ) within the configuration management tool Ansible.

## Install

### Installing the collection

To install this Ansible collection simply download the latest tarball and run the following command:

    $ ansible-galaxy collection install /path/to/middleware_automation.wildfly.tgz

Alternatively, you can simply build the tarball (and then install it):

    $ ansible-galaxy collection build
