# Random-Utilities
This is my hub for random utilities

Here is an example on how to create a file right from the web browser instead of creating it on the server.  Supports IE9+ and all others.  This is a UI specific chunk of code.

Ways to use:
1) Make an ajax call, send the results to fileSave.createFile(data, fileName);
2) Scrape some data off the page and save it to the users computer like a table set of data, or anything really.

Usage:
fileSave.createFile({data: [some data here], filename: 'yourFileName.txt'});

example:
fileSave.createFile({data: "this is the text for your file", filename: 'myawesomefile.txt'});

