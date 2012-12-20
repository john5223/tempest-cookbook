Description
===========

Installs the Openstack testing suite Tempest

http://github.com/openstack/tempest

Requirements
============

Chef 0.10.0 or higher required (for Chef environment use).

Platforms
--------

* Ubuntu-12.04

Recipes
=======

default
----
clones the tempest suite from github, and populates the tempest.conf by performing a chef search for the relevant details


Attributes
==========

Templates
=====
* `tempest.conf.erb` -config file for tempest


License and Author
==================

Author:: Jake Briggs (<jake.briggs@rackspace.com>)  

Copyright 2012, Rackspace US, Inc.  

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
