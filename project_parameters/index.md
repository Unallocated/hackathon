---
title: Project Parameters
---

Some of the projects that have been put together have been assembled with raw drunken genius.
The things achieved by this hackerspace are very unique and interesting and have pushed the
boundaries of technology. As these applications have become more entangled with the identity
of Unallocated Space and become expected in our everyday operation, we've found them harder
and harder to maintain, fix, or sometimes even turn on.

In this next iteration, we will be asking developers to go beyond just figuring out the intricate
curiosities of making the project work, and working to build interoperable and easily maintainable
software.

## APIs Everywhere
We want all of our systems to be able to talk to each other. Maybe we'll find a use for the [traffic light](/projects/traffic_light)
to talk to the [prolite sign](/projects/prolite) - they should have easy-to-use externally accessible
(within Unallocated Space) APIs. These should be extensible, respect the appropriate industry standards
specification (i.e. for web development, RESTful API standards should be applied).

## Documentation
Every project is expected to come with developer documentation. We're not looking for perfection, but
you should be able to pass your application off to somebody of some basic technical skill. This can
either be done manually, but automated documenting applications such as [doxygen](http://www.stack.nl/~dimitri/doxygen/)
or [sphinx](http://sphinx-doc.org/) (obviously use the appropriate document for the appropriate language).

We'd also like to see some planning documentation going into this, but there's no need to go nuts on this.
Just enough so that others can understand the vision of the project.

At this time, there is no specific software or method for the collection and collation of this. For the time
being, we will be allowing project leads to determine the best method for documenting their projects. This
may change based on our available resources.

#### External APIs
All externally accessible functions should be documented.  A short description, expected variables and their
types, and expected return. This is so that people can build other applications that interact with your
application.

#### README.txt
Each project should have a README file that gives a general overview of the project, project requirements, and systems
that the codebase is supported on.

#### INSTALL.txt
Each project should have a an INSTALL.txt file or similar that outlines how to install the application.

#### LICENSE.txt
Each project should include a LICENSE.txt. Each of these projects should be licenced under
[GPL v2](https://www.gnu.org/licenses/gpl-2.0.html) or [GPL v3](https://www.gnu.org/licenses/gpl.html). If for
some reason these licenses are not appropriate or are incompatible with the technology that is being used for
the project, please contact r00ster. If you need help picking an open source license, check out
[choosealicense.com](http://choosealicense.com/)

## Encapsulation
No production credentials will be distributed to the teams. All credentials must be placed into configuration
files and included dynamically into the applications. Default configuration examples should be set up in the
README file, and these configuration files should be excluded from the repository. This will allow us to publish
our work publicly and solicit work help from external sources without compromising our accounts or servers.

## Project Lead
Each project will require a project lead. This is somebody who can define the vision and the method for
the project. The project lead will also coordinate and make sure that all parts of the team are working
together. If there's a project that's been listed that doesn't have a project lead, or if you would like
to suggest a project, use the contact form to make these arrangements. [Learn more about becoming a project
lead.](/roles/projectlead)

## Github Repository
We're working to open source all of our core services code. We will be distributing these over Github
and open sourcing these projects to share them with the world. We'll need to get a github repository set
up under the Unallocated account. Use the Contact page to make these arrangements if necessary.

