# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course


EX. 11.1
So we have a project that is going to be written with Python and we
want to have a CI/CD setup.
Firstly for linting we have to use flake8 (https://flake8.pycqa.org/en) which is commonly used to check if our code conforms to the standard Python coding style.
For testing we are going to use pytest (https://docs.pytest.org/en).
And next we are going to atomate the build, when the build is automated, you are encouraged to commit frequently, usually
multiple times per day. It allows people to quickly find out about changes and notice if there’s a conflict between two developers.
The most commonly used tools for CI/CD are Jenkins and github actions but some good alternatives to these are CircleCI and Azure Pipelines. 
There are a lot of things that have to be concederd when choosing self hosting vs cloud hosting enviroment. We picked cloud hosting
because there is no Management responsibility.In Internally hosted environments need to be monitored and managed 24x7. 
In the cloud hosting model, the assets and/or applications utilized by a given enterprise don't reside within the enterprise, and are 
typically not directly controlled by the enterprise, at least at the infrastructure layer. The greater about cloud hosting is the Flexibility & Scalability
that cloud environments offer cause they have the ability to rapidly scale up and down as needed.