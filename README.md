# python-taurus-example

Taurus is an open-source automation tool used for load and also functional testing. Taurus acts as an abstraction layer on top of different load and functional tools, allowing users to easily maintain the YAML/JSON-based test scripts by storing them in the source control system.

## Create vEnv
python -m venv 'taurusEnv'

## Execute vEnv
soruce taturusEnv/Scripts/activate
## Install Taurus
pip install bzt

## Run yml script
bzt quick_test.yml