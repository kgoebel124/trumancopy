## Fall 2019 Semester Progress

Admin Mode Feature
=======================

This feature we are implementing allows for Admins to be able to edit any post, giving researchers the option to directly manipulate the actors/scripts via the Truman UI itself. 

The result is the option for a user deemed as Admin to be able to toggle Admin Mode on/off.

We started this process by playing around with a test page to see what would be the best way to make posts editable. We settled on using Semantic-UI's "contenteditable" feature as it appears clean and intuitive to use. 

When a user turns Admin Mode "on", a pop-up appears notifying the user of this switch. The captions, comments, like amounts, and photos of each post on the timeline can be edited when this mode is enabled. 

Future Developments
=======================

This semester we focused on the front-end component of the Admin feature. in the future, a backend component to this feature must be developed. This would include:

* Saving the updated posts to the database
* The option to export the contents of the database as a CSV


Truman Platform 
=======================

The Truman Platform is a fake social network for real results. This fake social network application allows researchers to create interesting and believable scenarios in a social network environment. Since the interactions that take place in a social setting and influence the outcome of an experiment, all content, users, interactions and notifications are “fake” and created by a set of digital actors. Each participant sees the same interactions and conversations, believe these to be unique to them. 

This allows any experiment to be completely replicated, and the tools can be repurposed for other studies. 

This current iteration is testing the bystander effect on cyberbullying. Future studies could be done on a number of other topics and issues. 

This project and software development was supported by the National Science Foundation through IIS-1405634. Special thanks to everyone at Cornell Social Media Lab in the Department of Communication. 

Also special thanks to Sahat Yalkabov and his [Hackathon Starter](https://github.com/sahat/hackathon-starter) project, which provided the basic organization for this project. 
