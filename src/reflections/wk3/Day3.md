# Day 3

Daily Challenge: https://github.com/NicoleMelone/spring21-gregslist

Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions

## What are the two common operations that we will set in the handler?
Get and Set

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?
Make sure the Get has the obj itself and the property it needs. Also need to make sure the property being accessed in not and id.

## What are some of the benefits of the proxy object that we are using in our structure for applications?
Proxys help override the get operator and help to prevent accessing the id!