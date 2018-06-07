# Omni-Notes Functional Test Plan

## Introduction
[Omni-Notes](https://omninotes.app/) is an open source note taking application for the Android operating system. This test plan describes its testing strategy, requirements and approach. The plan will define the test items and features that will be tested and their testing environments. 

## Testing Objectives

* Develop test plan for the system to ensure it is tested sufficiently prior to production.
* Prepare and execute Test Cases in accordance with the approved test plans.
* Identify the processes that will be used to document, track, report and manage issues that are identified during the testing phases.

## Scope
**Functional Testing**: Each functionality offered by the application will be tested to ensure it meets the set acceptance criteria. 


## Test Items
The application under test is my own fork of Omni-Notes hosted at [Github](https://github.com/andela-mkamau/Omni-Notes).

## Features to be tested
The following features will be tested:

* Notes actions: basic add, modify, archive, trash and delete notes actions
* Share, Merge and Search notes
* File attachment management
* Export and Import of notes
* Google Now integration


## Features not to be tested
Only functional testing will be performed for this application. Features that have not been described in this test plan will not be tested. This includes unit testing, security testing and any other integration testing.

## Item pass criteria
This completion criteria will be based at 100% test coverage of the tests done. A pass rate of 100% will be the exit criteria with all critical bugs having been fixed and there should be no major bug or blocker in the tests that fail.

**Suspension Criteria**

If the number of defects reaches a point where testing has no value, testing can be suspended. 

**Test Deliverables**

* Test Plan Document
* Test Cases
* Problem Reports and Corrective Actions


## Testing Stategy
Test planning, test conditions, test data, test cases and expected results will be documented. An acceptance criteria will be defined for each test case designed. 


The general strategy that will be use will be as follows:

1. Utilize Test Cases/Scripts and associated Test Plans from the business/user scenarios.
2. Prepare the Testing Environment.
3. Prepare/review detailed Test Data.
4. Run tests according to the test plan, recording all results in detail.
5. Analyze the test results in detail. Investigate in detail any discrepancies noted, creating and log defects with details.
6. Analyze defects and resolve, as needed, by working with the development team, and the test team.
7. Retest, as needed, once the defect is fixed and changes are completed.
8. Perform regression testing.


## Defect Tracking
Identifying defects is one of the primary reasons of testing. Defects will be classified as critical, high, medium or low in a descending order of severity. Each identified defect will logged, reported and tracked for fixing by the development team.
