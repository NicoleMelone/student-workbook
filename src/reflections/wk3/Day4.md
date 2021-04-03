# Day 4

Daily Challenge: https://github.com/lanericharddavis/sportinggoodsdepot

Read Advancing with JS > The Observer Pattern and answer the following questions

## What problems does the Observer Pattern seek to solve?
Data binding, updating parts of a page from events with data provided, and event driven binding.

## What are the three mechanisms of the observer pattern?
Subscribed, unsubscribed, broadcast. To add events, delete events, or execute all data bound events,

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
It makes a copy of the info then grabs the values of the object(s) and turns them into a string so they can be called in anywhere in the DOM to be manipluted or placed somewhere otherwise inaccessable. 