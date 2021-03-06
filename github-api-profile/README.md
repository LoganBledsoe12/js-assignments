# github-api-profile

## Description

This assignment serves to reinforce JS syntax, functions, and some mathematical operators and sequences.

## Objectives

### Learning Objectives

After completing this assignment, you should:

* Understand general JS syntax
* Grasp why functions are important
* Understand arrays and loops
* Be able to recite the meaning and importance of SOLID principles
* Be able to breakdown a complex sequence into a series of steps, use jQuery AJAX, handle callbacks and asynchronous code, and write to the DOM with JS

### Performance Objectives

After completing this assignment, you should be able to effectively create a simple website that utilizes HTML, CSS, and JS.

## Details

### Deliverables

* A publicly visible website on `gh-pages`

### Requirements

* No JSHint warnings or errors
* No JS errors in the browser
* All functions and code should work according to the following description.

## Easy Mode

Build a github profile app that prints out some info from the Github API and your repos. __For the design, you should recreate the Github Repos Tab to the best of your ability__.

> Github tab page: https://github.com/matthiasak?tab=repositories

The information from the Github API that you will display includes information from your github user account and repositories.

- Write `$.getJSON()` requests to:
    - `https://api.github.com/users/<username>`
    - `https://api.github.com/users/<username>/repos`

- After loading data from the Github API, write at least the following information to the DOM:
    - name
    - blog
    - location
    - email
    - avatar_url
    - html_url
    - and list all of your repositories

## Hard Mode

Use external template files. Your code will make AJAX requests to Github (for data) and your project directory (for HTML templates).

## Nightmare Mode

Create a `GithubClient` Constructor and Prototype chain that implements all the above functionality.

## Notes

Notes go here...

## Additional Resources

* Read []()
