Editing Mendip Story Circle Website
===============================

Using Github in General
-------------

The primary way to edit this site is to "fork" it, "commit" changes on the fork and then make a "Pull Request" to put the changes back here.

* fork : Copy the entire site into your own github account
* commit : Make a change and record the change as a kind of event
    You will need to add a note saying what you have done
* Pull Request : Request the changes in your fork be applied to the original (storyfeet/mendipstorycircle)

If you have already made a fork, before making changes, it's worth trying to 'fetch' changes made on the original.  This should be 1 or two clicks, to check if your fork is up to date.


Mendip Story Circle
-----------------

Adding a Member:

1. navigate to "assets/pics/members" upload an image file for that member.
2. commit the cha commit the change
3. In your fork, navigate to "\_members", and create a file called "&lt;member\_name&gt;.md"
4. add the that file the following contents:

```
---
title: <member_name>
photo: <photo_file_name.jpg>
categories: <either member or quartet>
---

Any information you wish to say about the member. (Remember the ':'s should have a space after them). 

If you don't have a photo, just don't include that line in the header.
```

5. Commit the change.
6. Create a pull request and if you can, merge it.


Adding an Event
------------

1. navigate to "\_posts/events"
2. Create a new file with the name "YYYY-MM-DD-event-name.md"
3. Inside that file all the folling contents

```
---
title: <event name>
---
Any info you wish to add about the event.
```
4. Commit the changes
5. Make and marge the pull request.


