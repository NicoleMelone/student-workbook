# Day 1

Daily Challenge: https://github.com/NicoleMelone/open-trivia

Read Asynchronous Code > Callback Hell and answer the following questions


### What are some of the signs and causes of Callback Hell?
You have a cascade of closing tags, one method goes on and on. Writing bad code is the biggest casuse of callback hell. You can easily fix this problem by pairing like things in one place and moving others to another place. 

### What does the asynchronous mean and how are callbacks involved?
It wraps generators and promises in a higher level syntax.

### Summarize the 3 ways to avoid / fix Callback Hell
Keep your code shallow - pairing like things together and having functions at top level
Modularize - having minimal code allows for an easier read and understanding of what each function or method does.
Handle every single error - It's important to be debuggering code from the beginning to end of each aspect of the DOM. Finding errors early on will make it easier to adjust everything after that. The try/catch allows an error to pop up immediately and the network can help locate where the error occured.

