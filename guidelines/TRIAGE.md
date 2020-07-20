# AlgoTradeX Issue Triage

## TL;DR

The purpose of this doc is to define a process for triaging AlgoTradeX issues.

## Objectives

* Establish well accepted criterion for determining whether issues have been triaged
* Establish a process for ensuring issues are triaged in a timely fashion
* Define metrics for measuring whether we are keeping up with issues

## Triage Conditions

The following are necessary and sufficient conditions for an issue to be considered triaged.

* The issue must have a label indicating which one of the following kinds of issues it is
  
  * **bug**
    * Something is not working as intended in general.
  * **discussion**
    * Discussion going on a certain topic
  * **duplicate**
    * Duplicate issues
  * **enhancement**
    * Everything is working as intended, but could be better
  * **feature request**
    * A new feature request that does not exist
  * **proposal**
    * Proposal to do/change/implement specifics
  * **question**
    * Clear question statement
    * Something is not working as intended in author's specific use case and he/she doesn't know why.
  

* The issue must have at least one area or platform label grouping related issues and relevant owners.

* The issue must have a priority attached to it. Here is a guideline for priority

  * **P0** - Urgent - Work must begin immediately to fix with a patch release:
    * Bugs that state that something is really broken and not working as intended.
    * Features/improvements that are blocking the next release.
  * **P1** - Rush - Work must be scheduled to assure issue will be fixed in the next release.
  * **P2** - Low - Never blocks a release, assigned to a relevant project backlog if applicable.
  * **P3** - Very Low - Non-critical or cosmetic issues that could and probably should eventually be fixed but have no specific schedule, assigned to a relavant project backlog if applicable.

* **P0** & **P1** issues must be attached to a Kanban board corresponding to the release it is targeting


## Process

Atx-Core team is responsible for ensuring new issues have an area or platform label

## Become a contributor

* Make sure that you have enough permissions to assign labels to an issue and add it to a project.

## Triage guideline

* Take an issue from "Needs Triage" project and open it in a new tab.
* Carefully read the description.
* Carefully read all comments below. (Some issues might be already resolved).
* Make sure that issue is still relevant. (Some issues might be open for months and still be relevant to current AlgoTradeX release whereas some might be outdated and can be closed).
* Ping one of the issue repliers if he/she is not replying for a while.
* Make sure that all triage conditions are satisfied.

## Metrics

We would like to begin to collect and track the following metrics

* Time to triage issues
* Issue volume
