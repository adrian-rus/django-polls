Django forum - adding polls

This project is extending the django-forum app by adding polls

Step 1
- created a new 'polls' app
- extended the Thread model to add Polls, Poll Subjects and Votes
- created new forms (PollForm and PollFormSubjects)
- collecting data from multiple forms in one go
- linked in jQuery to render the poll form

Step 2
- Creating a new 'thread_vote' view in threads.views.py
- Adding a custom template tag to ensure votes only go in once
- Editing 'thread.html' template to render the polls view
- Adding a vote filter in thread template tags to see how users are voting
- Linking the poll votes in the 'urls.py'

