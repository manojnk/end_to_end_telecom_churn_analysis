### end_to_end_telecom_churn_analysis

### Software and tools requirements
 -Bostonhousepricing
 -Software and tools requirement
 -Github Account
 -VS Code IDE
 -Heroku Account
 -Git CLI

Create a new Environment

***
conda create -p venv python==3.7 -y
***

shows an error H000 then

conda config --set ssl_verify false

after that run the create new environment line and then set back ssl_verify back to true

conda config --set ssl_verify True

To setup required laibraries

pip install -r requirement.txt

TO config user name and emailID (linked with github)

git config --global user.name "name" git config --globaluser.email "email"

git add and get status

git add . git status

to commit code

git commit -m " this commit includes requirement and readme file"

git push

git push git push origin main

