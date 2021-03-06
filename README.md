makesense (Managing Reproducible WSNs Experiments)
==================================================

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.15928.svg)](http://dx.doi.org/10.5281/zenodo.15928)

makesense is a high-level framework for automating scientific
experiments. Thanks for checking it out.

All documentation is in the "docs" directory and online at 

- First, read docs/installation.txt for instructions on installing
  makesense.

Installation
------------

1. Download the repository. If you have git installed type the following
   command :
  ```
  git clone git@github.com:sieben/makesense.git
  ```

2. Download Contiki from the following address to the root of the
   previously downloaded repository:
   [https://contiki-os.org](https://contiki-os.org)

3. Install all the system dependencies. If you are using ubuntu you can use the
   .travis.yml file as a way to help you.

4. Install the python dependencies by using:

  ```  
  pip install requierements.txt
  ```

Getting started
---------------

- Launch an experiments by using for instance:
    
       fab hello:run_all

This will run the experiment hello with all the defined tasks in the
exp.json

Code status
-----------

[![Requirements Status](https://requires.io/github/sieben/makesense/requirements.png?branch=master)](https://requires.io/github/sieben/makesense/requirements/?branch=master)

[![Build Status](https://api.travis-ci.org/sieben/makesense.png?branch=master)](http://travis-ci.org/sieben/makesense)

Licence
-------

makesense is released under the [Apache
License](http://www.opensource.org/licenses/Apache-2.0).
