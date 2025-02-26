# Docs

This is a repository that is consumed by the playbook at https://github.com/KakeiBro/docs-playbook. 
Everything inside of the `content` folder will be taken as components that will be 
used to build the docs site through the usage of the antora tool.

## Info on folder structure and patterns

Antora Docs has its own default folder structure that is understood as a convention 
when it comes to organizing the content and how this will affect the final rendering of 
the page, and also how references to different components will be resolved. 
[Standard Directories](https://docs.antora.org/antora/latest/standard-directories/)

## Description of the folder structure

- We have a `ROOT` folder with introductory details about the system.

## Access to the site

You can review the docs at [KakeiBro Docs](https://www.kakeibro.docs.dsbalderrama.top).

In case there are updates to the docs, every day at 00:00 UTC, a CRON Action publishes 
an updated website.