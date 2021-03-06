---
tags: [launch-code, programming]
title: LaunchCode Assignment 3
created: '2021-03-04T18:21:20.360Z'
modified: '2021-03-06T01:29:30.634Z'
---

# LaunchCode Assignment 3 #

- ~~Found todo #1 @ list-jobs.html~~
- ~~Found todo #2 @ list.html~~
- ~~Found todo #3 @ SearchController.java~~
- ~~Found todo #4 @ search.html~~


### Notes ###
sh -> Bourne Shell
bash -> Bourne Again Shell
fish -> Friendly Interactive Shell

- markdown syntax
~text~ -> stikes "text"

#### Breakdown of todo #2 in assignment
tableChoices = {
	"employer": [Employer, Employer],
	"location": [Location, Location],
	...
}

- list.html (line 25)
'category' would end up being something like this -> "location": [Location, Location]

- list.html (line 27)
'item' would end up being something like this -> Location

Encoding and decoding URLs: https://www.url-encode-decode.com/

Inspecting http://localhost:8080/list/jobs?column=positionType&value=Data%20Scientist%20/%20Business%20Intelligence

Query parameters being sent
column=positionType
value=Data Scientist / Business Intelligence

### What is Git? ###
Git is a version control system for projects.

```bash
git status
# Displays the changes that have been made to a Git repository

git add <path>
# Tells git to start tracking "<path>"

git log
# Displays a log of all commits made to a repository
```

### Bonus Mission #1 ###
- How to add attributes to an HTML element using thymeleaf
  - For the searchTerm input field
    - What property do we need to set in order to display the previous search term
