# DamlTicketing 
DamlTicketing is a simple ticketing system application built in Daml.

### I. Overview 
This project was created by using the `empty-skeleton` template.

A user (any party) can create a ticket, share the ticket with anyone and make comments on it with attachments' metadata. 

### II. Workflow
  1. A user created a ticket
  2. The organization assings the ticket to a support agent
  3. The agent and client reply to each other until the issue is solved
  4. Additional followers can be added by any user who is already an observer

### III. Limitation(s) and Challange(s)
* Did not implement proper organisation and user management.
* Could not implement adding a follower and making old comments on the ticket visible to them as well using a sinlge choice

### IV. Compiling & Testing
To compile and test, run the pre-written script in the `Testing.daml` under /daml OR run:
```
$ daml start
```