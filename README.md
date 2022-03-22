
# How to Host Your First Resume on GitHub Pages

## Purpose

The purpose of this document is to show step by step how to host a resume online using Markdown, Jekyll and GitHub Pages. This will also explore how these steps relate to the general principals of current technical writing described in Andrew Etter’s book [Modern Technical Writing.](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Prerequisites

The only prerequisite for this task is to have a resume ready for the desired position. However, it needs to be formatted in Markdown. So, It is recommended to have some prior research done on it.

Let's take a look at my [resume](https://github.com/deepta03/deepta03.github.io/blob/main/index.md) to see how a Markdown formatted document looks like.

To know more about Markdown and how to format a document using it, see [More Resources.](#more-resources)

## Instructions

Just as Andrew Etter mentioned in his book about static websites and GitHub Pages, this section of the document will guide you through hosting your resume online using GitHub Pages.

1. Sign up for a GitHub account [here.](https://github.com/signup)

2. Create a new repository by clicking the + button at the top right corner.

3. Choose `username.github.io` as the repository name where `username` is your GitHub username. This is required for your GitHub Pages website.

4. Once you have your repository ready, upload your Markdown formatted resume using the `Add File` button and rename it as `index.md`. Again, this is also a GitHub Pages requirement.

5. Select `Settings` under the repository name.

6. Find `Pages` on the sidebar.

7. Click `Change Theme` button.

8. Choose any theme of your choice. For our purposes, themes Leap Day and Architect work the best. Once you are done click `Select theme` to confirm.

9. Go to `username.github.io` to view your website.

![Resume](https://user-images.githubusercontent.com/102154139/159556666-3b9e06d4-aa77-4fef-8f53-569a18e532f4.gif)

## More Resources

* [Markdown Guide](https://www.markdownguide.org)

* Andrew Etter’s book [Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

* [GitHub Pages QuickStart](https://docs.github.com/en/pages/quickstart)

* [GitHub Pages Themes](https://github.com/pages-themes)

## Authors and Acknowledgments

**Jekyll Dinky Template by**

* Ben Balter
* Filipe Tavares
* Parker Moore

**Group members**

* Joshua Smallwood

## FAQs

**1. Why is Markdown better than a word processor?**

Andrew Etter nicely explained in his book why Markdown is a better choice than a Word processor. While Word processors do a good job at resume writing and editing or creating PDF, it does not support version control which is essential for documentation. Also, it is difficult to convert a Word file to HTML. On the other hand, Markdown supoorts version control and is suitable for creating websites. Therefore, the fact of it being free, easy to learn sets it apart from a word processior when it comes to documentation.

**2. Why is my resume not showing up?**

Follow each steps in the instructions carefully. Depending on the theme chosen, you might have to configure and update your your site's _config.yml. For more details, find your theme [here](https://github.com/pages-themes) and take a look at the README.md file.
