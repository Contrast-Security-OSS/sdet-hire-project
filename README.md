# Overview

The goal of this project is to create a conversation similar to one you would experience during a typical day working at Contrast Security as an engineer. You've made a pull request (PR) to a repository and are going through the code review process. It's the primary way we work from the infrastructure all the way through the front end code. 

As you are considering your approach, keep in mind that we are looking for the following:

* One or more well written defect tickets
* One or more automated tests on different levels.
* Distinction in the different kinds of testing.

You have complete freedom to work the project as you see fit. 

After the code review of this project you will have a strong understanding of what your day to day work life at Contrast will look like, experience with some of the team and experience with our product. 

# The Project

The project works has two components 

Black box testing:

* Install the Contrast Security agent and test the Community Addition
	* Report one or more defects in writing such that an engineer is likely to be able to repair the problem.
	* Create one or more tests to demonstrate the issue.
	* Create one or more API tests to demonstrate the issue. 

White box testing:

* Install the purposely vulneralbe open source WebGoat application.
  * Report one or more defects in writing to the opensource WebGoat project
  * Create one or more automated unit or integration tests and make a pull request to Webgoat.

**Important:** Our expectation is this project will take approximately 4 to 6 hours. You are free to use more or less time.

## Installation and Setup

The steps for this are:
* Fork this repo
* Setup use of the Contrast Community Edition

### Fork the Repo

Fork the repo to your github account. If privacy is an issue, please use a private repo and share it with `behemphi` who is the hiring manager. 

### Setting up the Contrast Security Community Edition 

**GOTCHA:** When you install WebGoat you are inviting attacks.  We strongly recommend installing this on a virtual machine locally or using the AWS account we will provide!

Follow the directions for [getting started with the Community Edition](https://www.contrastsecurity.com/contrast-community-edition) on our website.  Any problems you encounter are candidates for creating a defect ticket in your repo. 

You will be asked to demonstrate a working version of the Contrast either from your local machine or in AWS. 

#### Reporting a Defect

It is important to note that time is a factor. We don't want you to spend a day finding a big juicy bug. Indeed if you get to a reasonable time and you have not found a defect, simply create an artificial scenario that allows you to write the test automation you'd like to show off. _Your_ code is far more interesting in this exercise than any defect you might find. 

What is important is how you communicate the defect in writing. Things like reproducing the defect, specifying how it should work and the like are ideal.

#### Writing Tests

You are welcome to write tests that directly exercise the UI, however we are specifically interested in your ability to work with our API. PLease ensure you write one or more tests that exercise the API in a way that shows off the defect.

### WebGoat and White Box Testing

The purpose of this phase of the project is to provide you with a Java code base where you can create a unit, functional or integration test below and API layer.   

The [code for WebGoat](https://github.com/WebGoat/WebGoat) is also on Github. There is an existing integration test suite in place and there are a number of issues already reported on this project. 

Your task is to choose an existing issue and make an additon to the test suite and offer a pull request to the project. It is not important if the project accepts your PR, only that you made it.

What we are looking for in this phase is your ability to read someone elses Java application and making an addition to it within the existing framework.  We will also be looking at your code and making suggestions.

# Bonus Points

We work in a remote environment. High fidelity written communication is the key to maintaining velocity.  Showing off your ability to write effectively, provide screen shots, and generally expose your assumptions will go a long way.

# Feedback

If you find problems with these directions being unclear, make a PR on this project with a fix. 



