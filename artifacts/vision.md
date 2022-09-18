# To-Do List Application Vision Document

###### Created: September 11, 2022
###### Updated: 09-15-2022 @ 7:27 PM

&nbsp;
### Index

1. [Introduction](#1-introduction)
2. [Users & User-Level Goals](#2-users-user-level-goals)
3. [Summary of System Features](#3-summary-of-system-features)
4. [Project Risks](#4-project-risks)
5. [Glossary (Data Dictionary)](#5-glossary-data-dictionary)


&nbsp;
## 1 &nbsp; Introduction

To-Do List is an application aimed at helping users complete short-term tasks.

##### Client Requirements:

* allow creation & addition of tasks to the list
* enforce a max capacity for the list to limit number of tasks allowed to be on the list at once (i.e., eight tasks maximum)
* allow repositioning tasks on the list at any time
* enable user to mark a task as 'complete' when it has been finished irl
* allow user to send completed tasks to an archive, both individually and in bulk
* allow user to view the completed task archive at any time
* allow user to delete tasks from the archive, both individually and in bulk; this deletion will result in permanent loss of task data
* allow user to delete tasks from the (to-do) list, both individually and in bulk; this results in permanent loss of task data
* enable user to set a task as 'important'; all tasks are assumed to have equal priority, except tasks marked as important, which have the alternate & highest level of priority
* actively display the number of completed tasks versus total tasks on active list
* actively display the number of tasks added to the list, versus the capacity of the list
* keep track of the number of tasks completed from a date set by the user up to present; will refer to this as the 'task odometer'
* allow user to view task odometer at any time
* allow user to reset task odometer at any time
* the task odometer will display the date last reset, and the number of tasks completed from then up to the present


&nbsp;
## 2 &nbsp; Users & User-Level Goals

The following is a table containing users of the system, as well as their goals:

| User (Title) | Description of Goals |
|--------------|----------------------|
| Task Manager | add a task, edit a task, view task details, mark task as complete, delete task, send completed task to archive. |
| List Manager | view tasks on list, reposition tasks on list, reset contents of list. |
| Archive Manager | view contents of archive, remove content from archive, clear archive. |
| Progress Manager | view odometer, reset odometer. |


&nbsp;
## 3 &nbsp; Summary of System Features

The following is a list outling the system's features:

_"the system shall do" ..._

* task recording & storing
* task editing
* marking tasks as 'complete'
* task removal
* task archiving
* viewing of the to-do list
* viewing of task contents
* 


&nbsp;
## 4 &nbsp; Project Risks

The following is a chart containing all expected risks to project development, including a description and a rating of the risk's importance:

| Risk Name | Risk Description | Risk Level |
|-----------|------------------|------------|
| GUI Dev.  | Designing and implementing a simple & efficient GUI that suits the system. | Low |


&nbsp;
## 5 &nbsp; Glossary (Data Dictionary)

The following is a table containing a glossary term and its meaning within the context of the project:

| Term | Aliases | Description |
|------|---------|-------------|
| | |


&nbsp;

---
###### Prepared by R.C.H for To-Do List project, (C) 2022