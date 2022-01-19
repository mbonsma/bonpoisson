---
title: Here's an example of what a post looks like
subtitle: Simplifying the posting and review of blog posts for everyone
status: inactive 
#active if you want it on the frontpage

description: |
  This blog post has a long title, with a subtitle.
  Setting the `no-link` property means that there's no link.
#Don't use colons in any titles

people: # add peope that are involved in this project
  - jeremy
  - matt

layout: blog # do not change this
image: #'posts/forking/nice-fork.png'
last-updated: 2021-8-1
# do NOT add 0 (such as 06 for June). Will break everything lol
# take out the underscore in the name.
---

This is the text that will appear in the webpage, in Markdown.

To create a project, just create a markdown file in the `_projects` folder. Here are the things you can put in the YAML frontmatter:

- `title:` The project title.
- `notitle:` Set this to `true` if you don't want a title displayed on the project card. Optional.
- `description:` The text shown in the project card. It supports markdown.
- `people:` The people working on the project. This is a list of keys from the `_data/people.yml` file.
- `layout: project` This sets the layout of the actual project page. It should be set to `project`.
- `image:` The URL of an image for the project. This is shown on both the project page and the project card. Optional.
- `last-updated:` Date in the format of `YYYY-MM-DD`. The project cards are sorted by this, most recent first.
- `status: inactive` Set this to `inactive` if don't want the project to appear on the front page. Just ignore it otherwise.
- `link:` Set this to an external URL if this project has a page somewhere else on the web. If you don't have a `link:`, then the content of this markdown file (below the YAML frontmatter) will be this project's page.
- `no-link: true` Set this if you just don't want a project page for your project.

Links to github can be added like
[this](https://github.com/uoftbiophysics/).

Adding images is as simple as using an html command for images, such as this: <img src="/img/posts/forking/nice-fork.jpg" alt="idp" width="400px" align="right" style="padding:5px;">
Try to keep a nice hierarchy of images in our img folder.
