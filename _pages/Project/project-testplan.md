---
layout: assignment
permalink: /Project/TestPlan
title: "CS375: Software Engineering - Test Plan"

info:
  coursenum: CS375
  points: 100
  goals:
    - To produce a test plan including unit tests, output tests, and user acceptance tests

  rubric:
    - weight: 40
      description: Unit and Integration Tests
      preemerging: Unit/Integration tests are generally unclear, missing, or inappropriate for the project being tested
      beginning: Unit/Integration tests are present for some  of software methods or components, and somewhat clear and appropriate for the project being tested.
      progressing: Unit/Integration tests are given for a majority of software method or component, but some boundary or erroneous inputs are missing that would result in a more robust test plan
      proficient: Unit/Integration tests with appropriate inputs are given for a majority of software methods or components
    - weight: 40
      description: User Acceptance Tests
      preemerging: User acceptance test scripts are missing, unclear, or missing dependencies with respect to software requirements
      beginning: User acceptance test scripts are written for many software requirements and are cross-referenced with acceptance tests for many dependent requirements
      progressing: User acceptance test scripts are written in a mostly non-technical voice for nearly all software requirements and are cross-referenced with acceptance tests for dependent requirements
      proficient: User acceptance test scripts are written in a non-technical voice for all software requirements and are cross-referenced with acceptance tests for dependent requirements
    - weight: 20
      description: CI Automation
      preemerging: CI Automation is not present or insufficient
      beginning: CI Automation is partially present or partially sufficient.
      progressing: CI Automation is mostly sufficient and evidence exists of successful runs.
      proficient: CI Automation is fully sufficient and evidence exists of successful runs.

tags:
  - project
---

For the test plan, you will create a document that lists and describes all the tests that you will perform to validate your software project. These will become unit tests, integration or output tests, and user acceptance test scripts (that a non-technical user could follow to validate the functionality of your project).

You will develop each of these tests so that they can be performed on your software project, and the results documented in your final software report when the project is finished.

It is important that you achieve appropriate coverage for your tests. This means that your unit tests should achieve good code coverage for your project, and that your acceptance tests should cover all of your requirements.

### Unit Tests (White Box)

For each software component/method/decision branch, write unit tests that cover the primary use cases, boundary conditions, and error cases. Aim for meaningful coverage rather than a specific percentage — every test should be testing something that could actually break. If your code calls a database, external API or AI, use mocks.

### Integration Tests

For components that interact with real external systems — databases, or file systems — write integration tests that exercise the full stack against real infrastructure. Unlike unit tests, integration tests do not use mocks. They verify that your code works correctly with the actual systems it depends on in production.
If your project does not use any external systems, this section may not apply — document that reasoning in your test plan.
For external API's - mock using Unit Tests

### User Acceptance Testing

For each functional requirement, write a test script appropriate for a non-technical end user. The script should describe the steps to exercise the requirement and the expected result if it executed correctly. If a test depends on another requirement being satisfied first, note that as a precondition and reference the relevant acceptance test by number.

### Automation

Create a GitHub Actions workflow that runs your unit tests and coverage report on every commit. If you have integration tests, add a second job that runs them against a service container. We demonstrated both of these patterns in class — use the demo repository's ci.yml as your starting point and adapt it for your language and test runner.

### Website

Include your report on the project website.
