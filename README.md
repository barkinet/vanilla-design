# vanilla-design
Design patterns for Vanilla Framework
Jump to contentHomeTopics
Design
Development
Notes
Research
User Experience
ArchivesTeamSearch:Searchubuntu design blog
Designing in the open
 Anthony's photo Anthony Dillon Posted on 25th April 2017Filed under: Design Development User Experience
Share this article:
Share on Twitter
Share via Email
Share on Facebook
Share on Google+
Over the past year, a change has emerged in the design team here at Canonical: we’ve started designing our websites and apps in public GitHub repositories, and therefore sharing the entire design process with the world.

One of the main things we wanted to improve was the design sign off process whilst increasing visibility for developers of which design was the final one among numerous iterations and inconsistent labelling of files and folders.

Here is the process we developed and have been using on multiple projects.

The process
Design work items are initiated by creating a GitHub issue on the design repository relating to the project. Each project consists of two repositories: one for the code base and another for designs. The work item issue contains a short descriptive title followed by a detailed description of the problem or feature.


Code block styling from https://github.com/ubuntudesign/vanilla-design/issues/12

Once the designer has created one or more designs to present, they upload them to the issue with a description. Each image is titled with a version number to help reference in subsequent comments.

Whenever the designer updates the GitHub issue everyone who is watching the project receives an email update. It is important for anyone interested or with a stake in the project to watch the design repositories that are relevant to them.

The designer can continue to iterate on the task safe in the knowledge that everyone can see the designs in their own time and provide feedback if needed. The feedback that comes in at this stage is welcomed, as early feedback is usually better than late.

As iterations of the design are created, the designer simply adds them to the existing issue with a comment of the changes they made and any feedback from any review meetings.


Table with actions design from MAAS project

When the design is finalised a pull request is created and linked to the GitHub issue, by adding “Fixes #111” (where #111 is the number of the original issue) to the pull request description. The pull request contains the final design in a folder structure that makes sense for the project.

Just like with code, the pull request is then approved by another designer or the person with the final say. This may seem like an extra step, but it allows another person to look through the issue and make sure the design completes the design goal. On smaller teams, this pull request can be approved by a stakeholder or developer.

Once the pull request is approved it can be merged. This will close and archive the issue and add the final design to the code section of the design repository.

That’s it!

Benefits
If all designers and developers of a project subscribe to the design repository, they will be included in the iterative design process with plenty of email reminders. This increases the visibility of designs in progress to stakeholders, developers and other designers, allowing for wider feedback at all stages of the design process.

Another benefit of this process is having a full history of decisions made and the evolution of a design all contained within a single page.

If your project is open source, this process makes your designs available to your community or anyone that is interested in the product automatically. This means that anyone who wants to contribute to the project has access to all the information and assets as the team members.

The code section of the design repository becomes the home for all signed off designs. If a developer is ever unsure as to what something should look like, they can reference the relevant folder in the design repository and be confident that it is the latest design.

Canonical is largely a company of remote workers and sometimes conversations are not documented, this means some people will be aware of the decisions and conversations. This design process has helped with the issue, as designs and discussions are all in a single place, with nicely laid out emails for all changes that anyone may be interested.

Conclusion
This process has helped our team improve velocity and transparency. Is this something you’ve considered or have done in your own projects? Let us know in the comments, we’d love to hear of any way we can improve the process.

Add your comment

Your name (required) 
Your email (required) 
Your website 
Your comment (required) 
Submit Comment
Join us!

Passionate about good design and creating delightful experiences? We’re looking for people who love to learn and share their knowledge and ideas.

See all the design jobs on canonical.com

Follow
@ubuntudesigners on Twitter
Make Ubuntu
Brand guidelines
© 2017 Canonical Ltd. Ubuntu and Canonical are registered trademarks of Canonical Ltd.Report a bug on this siteRSS feedhttp://canonical.comBack to top
