# Day 2
__02/09/21__

## What is a github action and how do they work?

Github actions are githubs solution to automating the processes involved in committing. They create unique instances of virtual machines that run yaml files, this allows for convenient integration testing and peace of mind.

## What benefits do github actions provide?

They can provide an absolute level of protection for live websites. Humans aren't perfect and I wouldn't put it past a developer to forget to run their code thruogh the tests before pushing to github. But having the tests perform on push creates an extra layer of security.

## What types of trigger actions can a workflow use? What do they do?

Workflow, Scheduled, Webhooks, External
These can be used to set different conditions for when the code should be tested. You can make it happen on commits, set regular times. intervals for it to be tested, or even "manually" trigger the tests just to be sure.