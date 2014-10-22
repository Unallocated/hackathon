---
collection: projects
layout: projects
title: Events API

git_project_link: https://github.com/Unallocated/EventsAPI
project_lead: Usako
project_languages: Python
project_other_techs:

---

The Events API is a one point broadcast method for disseminating event information to all social media used by UAS.

Currently, there is code for Meetup, Twitter and Facebook written in python.

Steps to accomplish during the UAS Hackathon:

 * Evaluate the current code vs. current API for each service (Meetup, Twitter, Facebook).
 * Create additional modules for remaining services (Google Calendar).
 * Design and create a Restful webservice that will trigger the multiple client modules to post to each social media/content service.
 * Create a test client purely for testing purposes.