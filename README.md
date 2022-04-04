
![alt text](./meguszos.jpg)


# Testing a website

## Story

Welcome to your first team-work project in this course.
From this week on, you are going to work in teams (4-5 people).
These exercises will simulate a real-life experience.
In a QA team, it is not uncommon that more testers work on the same product.
So the earlier you get used to working as a team, the better you will be able to communicate, solve problems, and
become excellent team-players. The System Under Test (SUT) this time will be the famous Internet Movie Database,
aka the [IMDb website](https://www.imdb.com/).
In the tasks list, you will find user stories that your team needs to write test cases for.

### Expectations

- Use Excel tables for your test cases
- Everyone on the team must work with the same format and in the same document - eg. Google Sheets
- Design tests consciously, based on ISTQB suggestions
- Make sure your Manual Test Cases can be executed by other Testers, even without the knowledge of the specific software
- Use a critical approach about the software, feel free to open a Bug in the Bug Tracking Project if:

    - something is not working that was specified in the Requirements
    - you experience suspicious behaviour

## What are you going to learn?

- Analyze and test a yet unknown software/website
- Design and implement manual test cases for functions
- Report Bugs (in Jira)
- Practicing your knowledge based on ISTQB suggestions
- Critical thinking

## Tasks

1. Successful login to the IMDb account with
    - As a registered user, I want to log in to my IMDb account, so that I can use most functionalities

2. Successful logout from the IMDb account
    - As a signed-in user, I want to log out from my IMDb account, so that I can protect my private data

3. Uploading a picture to the profile
    - As a signed-in user, I want to upload a picture to my profile successfully

4. Validating some of the Oscar winners in 2005
    - Winner of the Best Motion Picture in 2005 should be Million Dollar Baby
    - Winner of the Best Performance by an Actress in a Leading Role picture in 2005 should be Hilary Swank

5. Create a list that will contain people
    - As a signed-in user, I want to create a private list that will contain actors/actresses

6. Edit the list
    - As a signed-in user, I want to add 3 of my favourite actors/actresses to the list
    - As a signed-in user, I want to edit the title of my list
    - As a signed-in user, I want to edit the description of my list

## General requirements

- Use the terminal and Git commands to upload your work to the base repository

## Hints

- Explore the system’s behaviour before designing the test cases
- Use your browser in incognito mode when executing the tests
- Example test cases for a login:
    - Empty credentials
    - Wrong password
    - Successful Login
- If you wish, you can report found bugs into Jira - just create a project in Jira with this name format “Website testing - _the name of your team_“
- Do not forget: _"Anything that can go wrong will go wrong"_

## Background materials

- <i class="far fa-exclamation"></i> [How to Write Test Cases for Software (with a sample)](https://blog.testlodge.com/how-to-write-test-cases-for-software-with-sample/)
