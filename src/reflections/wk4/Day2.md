# Day 2

Daily Challenge: https://github.com/NicoleMelone/spring21-gregslist-mvc

Read Asynchronous Code > JavaScript Promises and answer the following questions

## What are the three states of a Promise?
Pending - sent the request and waiting for the response.
Resolved - the request came back as expected.
Rejected - the request did not come back as expected and will produce an error.

## How do promises seek to resolve the issues of "callback hell"?
The firstRequest is sent then the second and possibly so on. At the end of the sequence of requests .catch can be used to grab ALL the errors in itself leaving only the one callback instead of the same number of requests.

## What is the difference between .then() and .catch()?
.then is saying another request needs to be sent and can be sent right after the last one. 
.catch is saying there are no more requests that need sent and if any of the requests fail the error will pop up.