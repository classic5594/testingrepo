---
name: 1st Time Contributor Template
about: Use this template as a 1st time contributor
title: ''
labels: good first issue
assignees: ''

---

## Contribution Guidelines
Welcome to Section’s Engineering Education program. This program is dedicated to providing a community-generated pool of educational content that is useful for engineers of every level. To begin, we’d recommend reviewing our most recently published content at section.io/engineering-education/ to get a sense of:

- Article structures
- Type of content that has been contributed
- Topics you can begin working on

Articles do not need to be Section-specific or strongly Section-related. This is not necessarily about Section or Edge Compute directly, but rather an effort to provide educational value to software developers within the diverse ecosystem of web technologies. 

**Articles should be a minimum of 750 words.**

In order to participate in the program, all members will be required to agree to established [terms and conditions](https://www.section.io/legal-stuff/engineering-education-terms/). (Agreement is included as part of the enrollment process.)

In order to achieve a level of consistent style and increasingly elevated quality, we have created this document to help new contributors. Let's start by reviewing what's needed.

## Requirements for New Contributors
- GitHub account
- Text editor, such as [Visual Studio Code](https://code.visualstudio.com/), [Sublime Text](https://www.sublimetext.com/), [Atom](https://atom.io/)
- Prepared Markdown (.md) file. (Note: All articles must be submitted in properly-formatted Markdown.)
- PayPal account. (At this time, we only service payments through PayPal. If you don’t have a PayPal account, please check whether [PayPal is available in your region](https://www.paypal.com/en/webapps/mpp/country-worldwide).)
- To expedite reviews, publishing, and payouts for articles, we request that all first drafts are submitted error-free (pre-checked for English grammar, technically accurate,   properly cited, etc.) and meet our suggested article guidelines as outlined below.

All contributors are expected to review and adhere to [Our Code of Conduct](https://github.com/section-io/engineering-education/blob/master/CODE_OF_CONDUCT.md) before submitting articles.

## Suggesting a topic
Be sure to search for similar ideas in our published articles and #eng-ed-topics channel in Slack to help avoid overlap, ensuring that you are bringing a unique viewpoint to your suggested topic. If there are related articles that have been published, have a think about how you can build off those to bring additional value that hasn’t already been presented.
 
 
Once you have narrowed your topic search to one you would like to write about, fill out the [EngEd Content Idea Suggestion form](https://forms.gle/3PdJatmhFhCToMfp9) with your article suggestion. This will help you to think through and frame your content, while giving us a better idea of the key takeaways that you intend to communicate to your audience.

Once your topic has been approved and you have a final draft of your article ready  to submit, follow these [step-by-step instructions](https://github.com/section-io/engineering-education/blob/master/UPLOAD_INSTRUCTIONS.md).The instructions walk through how to submit a PR (pull request) in Github with  your fully prepared article.

## Submitting your article
Ensure all article submissions are pre-checked for English grammar technically accurate, and delivered under the assertion that the content is original to you and includes proper citations (including sourced images).


Before submitting your article, we request that you cross-check the readability of your content using this [free tool](http://www.hemingwayapp.com/). This check helps make your writing BOLD & CLEAR by calling attention to any lengthy, complex sentences and common errors. If you see a yellow sentence, you may want to shorten or split it. 


These guidelines are intended to help EngEd contributors grow as authors and to enrich the larger engineering community as a whole by continuing to create higher quality educational articles, tutorials, how-to’s,technology reviews, etc. 

Communicating your key takeaways
Articles should be clear, accurate, and fully explained. We are more interested in substance than length, and supporting examples are always encouraged. At the same time, articles that include mostly code with very little narrative lack sufficient depth and guidance for the audience to fully grasp important concepts.

We suggest you think about what is most important to your article or any pain point you are addressing. Assume the audience is smart but has no prior exposure to the common terminology in your article.


For example:
If your article is about serving ML models with Django, then the reader should have a decent understanding of something like: 

1) The structure of a django app
2) How to use such an app to serve a model for inference

The details your article gives should help further grow the readers’ skills as they practice on their own projects.

## Review and approval processes
Once you have opened a PR with your fully prepared article and accompanying images (according to the provided instructions), it enters a queue of articles to be reviewed by our technical review committee. Any required edits will be requested via comments within the PR in GitHub.  Articles will either be approved (for publishing) or sent back with requested revisions. Note: articles requiring very few edits will be given priority in the review queue, and we reserve the right to refuse any articles that do not adhere to quality standards.PRs with no response from members (comments, edits) after a period of 10 days will be closed (but are able to be reopened if needed).

As a community, we are continually striving to add value to our content pool through trusted pieces of content that help enrich the larger engineering community.

*Below you will find MORE examples to reference and help guide you write fantastic content!*

Please do not hesitate to reach out at any time  - we’re always happy to help.

---

## Example Format Structure 

Content can include:
- How-to guides
- Tutorials
- Software reviews
- New technology introductions/overviews

Suggested topic areas (but certainly not limited to):
- Network Engineering
- DNS Routing 
- BGP
- Caching
- Web Application Firewall
- Servers
- Reverse Proxy Technology
- Kubernetes
- Docker
- Cloud Native Technologies

## How-To (use) Guides:
#### What is the Scope and Purpose of the Guide

Introduce the audience to the software or tech you are writing about and explain what is its purpose, and be sure to highlight any of its main benefits and features.

Introduce the purpose of your How-To Guide, what functionalities of the proposed software will you be covering? 
Assume the reader is smart but has no prior exposure to any common terminology or prerequisites about the topic. (cite other EngEd articles or sources if applicable)

#### How-To Guides Overview 

Provide a brief description of the overall processes of the software, and how the user may need to work with the system. 
When needed, reference related processes and corresponding sources 

- Give Step-by-Step Instructions for using the software or system
- Instructions
- Conventions
- Errors, Malfunctions, and Emergencies
- Quick-Reference tips
- Screenshots

(You may choose to include a process flow diagram to accompany the text. Consider including images and/or diagrams throughout your guide to introduce the audience to new workflows)

## Tutorials Format:
To ensure the audience is getting the best experience - make sure you research other tutorials on the subject - this will help make you write a more complete and unique tutorial with a higher chance of being found and helping someone out. This also helps to narrow your focus as you research and begin to write. A bit of history about the technology being referenced or talked about might be helpful for the beginner audience.


Before starting make sure you pinpoint the problem your article is going to solve for the audience. If you are writing a tutorial, it is because you have noticed a pain point you’d like to address.
When framing your tutorial it would help to identify your audience - who is this tutorial going to be written for - and who will be reading it.
Tell the audience what a successful task looks like - and guide them through the process.
Make the tutorial as user-friendly as possible - by including screenshots, tips, code examples, anything you think would benefit the audience as they try to replicate the tutorial.
Don’t forget to get the audience involved by asking for feedback - or leave a call to action - for the reader to try out the skill they just learned about.

## Tutorial Format Example

- Title
- Introduction
- Goals (Optional)
- Prerequisites
- Step 1 — What to do first
- Step 2 — What to do next
- Step n — What to do last
- Conclusion

## Software Reviews:
#### Detailed Code Review Checklist

- Be Fair: When comparing software(s) - be sure to include both the advantages and disadvantages of the software being compared or reviewed
- Share why you believe this review to be helpful - describe your experience with the software (including extensive screenshots when applicable) - what problem did the software solve for you?
- Test, Learn, & Test again: - Take your time researching new interesting topics you choose to explore & ensure any included code blocks have been thoroughly tested - exactly as stated in the review - to help cut down revision time.
- Share any tips, techniques, and tricks you’ve discovered along the way, what helped you improve your coding experience - do not shy away from including details that may help the audience along the way.
- Coding best practices & Proper code formatting: While writing your software review, check the code formatting to help improve readability and ensure that there are no barriers for the audience to get started:
- Non Technical requirements: (Readability is very important) Get a feel of a story reading while reading through the software review. 

## New Tech Introductions Reviews:
- What new and exciting technology are you going to research and write about?
- Why are you introducing the EngEd community to this new technology - what is exciting about it?
- Who will be the most exciting about this new tech - who is the ideal audience in your mind that would benefit from the review?
- Layout any needed background information on the new tech being introduced.
- Include any needed background on the situation, industry, or in the literature to best explain the new technology.

## New Tech Introductions Review Format Example:
- BRIEF SUMMARY- Your tech introduction should be a self-contained topic and must be an accurate interpretation of what is presented.
- INTRODUCTION of the NEW TECHNOLOGY – a short introduction/description of the technology that is being reviewed.	 The introduction should contain all needed technical detail for the audience to replicate themselves and it should give the reader a clear understanding of how the technology works.
- POSSIBLE APPLICATIONS  of the new tech – explain how you have used this technology or how this technology may be used in the future.
- PROS & CONS– outline the advantages and disadvantages of this new technology from your own experience/point of view and support it using relevant examples and sources.
- CONCLUSION -  include any next or final steps summarizing the technology introduction - that serves as a good launchpad for the audience.

Other subject matter samples:
- https://www.section.io/blog/prometheus-querying/
- https://www.section.io/blog/debug-headers-best-practices/
- https://www.section.io/blog/real-user-monitoring-performance-optimization/
- https://www.section.io/blog/varnish-cache-503-error-guru-meditation/
