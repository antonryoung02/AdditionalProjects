# Project Collection

A set of additional projects  

## HostGPT
An application that uses Google Cloud, Pinecone, and ChatGPT to take user orders like a host at a restaurant.

## Designr
An unfinished social media marketplace application with Swift and Django

## CalendarGPT
204 Web Development final project, visible at: https://cse204-2023.github.io/10-final-project-antonryoung02/

Application built with react, schedules and tags events with ChatGPT using natural language.
A lot of the calendar apps I've used are quite tedious to maintain. You have to manually add each event to their corresponding days, set tags, etc.

The OpenAI API is used as a text-to-json formatter which does all of this for you. The API is called in 2 different scenarios.

1. New event is added -> Format to JSON with date, existing tag, and event content inferred from user input.
2. New tag is added -> Send all existing events without tags and see if the new tag applies.



