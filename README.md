# README

## Table of Contents
* [Introduction](#Introduction)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Loading Seed Data](#loading-seed-data)
* [Contributors](#contributors)
* [License](#license)
* [Changelog](#changelog)


## Introduction

I created this data entry application as a tool for a future project. The age old saying in database is garbage in, garbage out. With this program I aim to avoid that pitfall with easily readable and updatable forms in the front end, and validations to insure data integrity

## Getting Started
To get started the database must be loaded. To do so navigate to the backend/ folder and use the rails command `rails db:migrate`. Once the database is loaded and the schema is created, navigate to the frontend/ folder and in your browser open the file index.html.
To view the commits during the creation of this project, navigate to the respective github repo. For the frontend goto: https://github.com/VladDaImpaler18/testImporter_frontend
For the backend goto: https://github.com/VladDaImpaler18/testImporter_backend

## Usage
From the navigation bar the you can create questions, or view the list of available questions. When creating a question, you can choose an existing category or create one simply by typing it in the input bar, or selecting one of the already created categories that may appear in the dropdown. When looking at the list of existing questions you can filter by category to narrow down the list. Clicking on a question will open up it's information which allows you to view and edit the question.


## Loading Seed Data
For demonstration purposes, there are preloaded questions and categories. Load the seed data by navigating to the backend/ directory and using the command ```rake db:seed``` this will load dummy data for demoing purposes. 

## Contributors
If you would like to contribute fork the github repo, create your feature branch, commit changes and push the branch.

## License
(c) 2020 Vladimir Jimenez, all rights reserved. For Online Software Engineering PT - Javascript Project

## Changelog
Version 1.0 (11/29/2020) Initial Release