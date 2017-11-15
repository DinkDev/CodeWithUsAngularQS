# CodeWithUsAngularQS - my progress on "Code with us: Angular Quickstart" by John Papa and Ward Bell

## What is this?

This repo holds my progress for the Pluralsight course, "[Code with us: Angular Quickstart](https://app.pluralsight.com/library/courses/code-with-us-angular-quick-start)".

The primary application is a harness that runs each section (AKA chapter) within a central window.
Select a course section from the dropdown at the top and see that section's finished code running in the browser.

Almost everything of interest is in the `app/` folder where you'll find the code for each section of the course (including exercises) in its own folder. The `AppComponent` is the harness shell and the `AppModule` registers each section in the harness.
Each section folder is a standalone application that represents the end-state of the corresponding section in the course.

See the ["Final Project Walk-through" clip](https://app.pluralsight.com/player?course=code-with-us-angular-quick-start&author=john-papa&name=code-with-us-angular-quick-start-m1&clip=0&mode=live) that shows the harness in action. It explains how the harness works and how to run a section outside the harness.

The balance of this README comes straight from the Angular Quickstart (the course starting point).
It covers how to install and run the application. It also covers running the tests.
We didn't do much testing in this course but we hope that you'll be inspired to make testing part of your Angular development life.

## Install npm packages

Install the npm packages described in the `package.json` and verify that it works:

```bash
npm install
npm start
```