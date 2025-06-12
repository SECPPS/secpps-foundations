# Use a GitHub Wiki for Collaboration

## Context and Problem Statement

The SECPPS community aims to create a foundantional knowledge base collecting fundamental knowledge for the SECPPS field.

## Decision Drivers

* Easy browsing
* Easy editing
* Hosted without single responsibility
* Editable offline

## Considered Options

* GitHub wiki
* GitHub repository
* GitLab services
* Self-hosted wiki

## Decision Outcome

Chosen option: "GitHub wiki", because comes out best (see below).

### Consequences

* Good, because free, nearly world-wide accessible service
* Bad, because

## Pros and Cons of the Options

### GitHub wiki

* Good, because everyone with a GitHub account can edit
* Good, because browsing of the Wiki is easy
* Bad, because [navigation pane shoulbe be manually maintained](https://github.com/orgs/community/discussions/23914#discussioncomment-3242152)
* Bad, because a GitHub account is needed for editing

### GitHub repository

* Good, because both direct contributions and reviewed contributions (via PRs) are possible
* Good, because, Markdown is rendered by GitHub
* Good, because allows for git-based access
* Bad, because navigation through the knowledge base is more code-like and less then Wiki-like.

### GitLab services

* Bad, because less used as GitHub

### Self-hosted wiki

* Good, because a Wiki software with a nice UX can be used
* Bad, because single responsiblity
