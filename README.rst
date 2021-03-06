RestGate
========


.. image:: https://travis-ci.org/cloudnative/restgate-py.png?branch=master
   :target: https://travis-ci.org/cloudnative/restgate-py
   :alt: Travis Build Status

.. image:: https://coveralls.io/repos/cloudnative/restgate-py/badge.svg?branch=master&service=github
   :target: https://coveralls.io/github/cloudnative/restgate-py?branch=master

RestGate is a python library for communicating with a RESTful API hosted on AWS API Gateway.



Usage
-----

You can add RestGate using the usual PyPI channels. Example:

::

    pip install restgate

You can find the package details here: https://pypi.python.org/pypi/restgate

Alternatively, if you prefer to install from source:

::

    git clone git@github.com:cloudnative/restgate.git
    cd restgate
    python setup.py install



Wiki
----

Can be found here: https://github.com/cloudnative/restgate-py/wiki


Source Code
-----------

The Python source code for RestGate is available on GitHub:

https://github.com/cloudnative/restgate-py


Developing
----------

A really nice TDD flow can be created by running

::

    docker-compose run restgate sniffer -x--rednose



About CloudNative
-----------------

`CloudNative <https://cloudnative.io/>`__ is on a mission to codify the best practices for running a service in the cloud. If you are looking for help with AWS, please contact us.


License
-------

Copyright 2015 CloudNative, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0 Unless required by applicable
law or agreed to in writing, software distributed under the License is
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied. See the License for the specific
language governing permissions and limitations under the License.
