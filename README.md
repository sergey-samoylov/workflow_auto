# Workflow automation bash script

Just check the script, taylor to your liking if needed, make it executable & run

![script to run](https://github.com/sergey-samoylov/workflow_auto/blob/main/img/workflow_auto1.png)

The script will:
- create workflow folders as needed,
- git add .
- git commit -m "Your message" (by default just adds date to commit message)
- git push

![script to run](https://github.com/sergey-samoylov/workflow_auto/blob/main/img/workflow_auto2.png)

As for workflow... It creates by default:
- isolated Ubuntu env
- does actions checkout
- in Python of your choice
- pip installs flake8 in that env
- runs requirements.txt installs
- checks code of your project files for PEP8 rules

If these auto tests went without a hitch, you can place 

"your project passing" button in README.md file

[![Workflow automation](https://github.com/sergey-samoylov/workflow_auto/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/sergey-samoylov/workflow_auto/actions/workflows/main.yml)

Please, check my other [recent projects](https://github.com/sergey-samoylov?tab=repositories) for more.
