# Guide to using Journal

## Introduction

I was looking at ways to create a daily code journal and also a cool way of writing daily standup notes.

Found [jrnl](http://jrnl.sh/index.html) to be a decent solution and created this repo to share.

## Setup

* Added an extra Journal for Standup ()
* Added some functions to be added to the `bash-profile`
    * Load the Journal Settings - `jrnl_settings`
    * Open a new Journal entry - `jrnl_standup`
* Added a template file for the Standup Journal - `journal_template_standup.txt`

## Installation

`brew install jrnl`

(Also dependantant on using Visual Studio Code)

Add the bash functions
Update the `jrnl_config`

Make a directory to hold the Journals
`mkdir ~/Documents/journal`

Add the new template file

## Usage

To start a Standup Journal

`jrnl_standup`

Edit the file and save.

To view the latest entry

`jrnl stand-up -1`