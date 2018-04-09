# Guide to using Journal

## Introduction

I was looking at ways to create a daily code journal and also a cool way of writing daily standup notes.

Found [jrnl](http://jrnl.sh/index.html) to be a decent solution and created this repo to share.

## Setup

* Added an extra Journal for Standup
* Added some functions to be added to the `bash-profile`
    * Load the Journal Settings
    * Load a new `jrnl_standup` Journal entry
* Added a template file for the Standup Journal

## Installation

`brew install jrnl`

(Also dependantant on using Visual Studio Code)

Add the bash functions
Update the `jrnl_config`

Add the new template file

## Usage

To start a Standup Journal

`jrnl_standup`

Edit the file and save.

To view the latest entry

`jrnl stand-up -1`