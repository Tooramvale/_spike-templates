Spike Plan
==============
**Name**:

## Context:
Outline the reason and context for the spike.

Example: Team needs to use a database to store data for application developed
during this subject and must learn to use the Firebird DBMS tools to be able to
script the creation and population of the database.

**Knowledge Gap:**

**Skill Gap:**

**Technology Gap:**

Provide details of the appropriate gaps related to this spike.

Example: The team is not familiar with the Firebird DBMS that has been chosen by
the subject conveners. Need to install and make use of the following tools for
Firebird:
- FSQL command line tool
- FlameRobin GUI admin tool

## Goals/Deliverables:
What are the goals and deliverables of this spike?
Example:
- Scripts need to create database that models the application domain
- Scripts to insert initial test data into the database
- Batch file, makefile or MSBuild script that includes database setup and tear
  down

**Planned start date:**  Example: 13/08/2017

**Deadline:**  Example: 20/08/2017

## Planning notes:
Outline a proposed plan of how this spike can be undertaken.

Example:
- Design database tables for the team’s application domain.
- Install and configure fsql and flamerobin with embedded Firebird driver if
  required
- Create scripts to construct the database tables
- Create scripts to populate the database tables with initial test data
- Create scripts to tear down database
- Create batch/makefile/build script with two targets, one to construct and
  populate (setup) the database, and the other to tear down the database.
