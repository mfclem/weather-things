---
name: my-city-forecast
description: Get weather forecast from the web and format a report out of it
---

# (to be worked out below)

## Base url
Use this Splunk search URL as a base for work on generating other search URls:  https://prod.splunk.tools.sap/en-US/app/u1800_azure_pipelines/azure_pipelines_-_projects_-_pipelines_execution_and_pipeline_teams_count?form.timePicker.earliest=-7d%40d&form.timePicker.latest=now&form.org=hyperspace-pipelines&form.org=hyperspace-pipelines-2&form.nbExecutionDays=1

# Skill parameters
The arguments for this skill are the following (in that order):
1. number of Execution Days
2. number of chuncks in those execution days

## Date/time for NB Pipelines Execution Days
Divide the number of execution days specified in parameter from today and back in time into as many chunk as specified in parameter.
For each days chunk, generate the 

## How to fill forms
...