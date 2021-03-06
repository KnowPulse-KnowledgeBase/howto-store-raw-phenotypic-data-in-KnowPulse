---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "How can I store my raw phenotypic data in KnowPulse"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson will show you how to use KnowPulse's raw phenotype importer to backup/upload/download/view your data files. "

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Pulse Crop Researchers focused on variation data."

# A comma-separated list of maintainers for this lesson.
maintainers: "Ruobin Liu and Reynold Tan"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "This lesson is aiming to guide our pulse crop researchers through the procedure of raw phenotypic data managing. KnowPulse can be used to store your raw phenotypic data; we highly recommend backing up your data regularly in KnowPulse during the growing season. At the end of the season, you can download your data from KnowPulse for your next step data analysis and interpretation."

# A short list of items researchers will learn in this lesson.
learn:
- "How to set up a project on KnowPulse to host your data"
- "How to enter raw phenotypic data into a data collection spreadsheet" 
- "How to backup and upload raw phenotypic data files"
- "How to download and view your data files"

data-description: "Phenotypic Data."
---

The KnowPulse KnowledgeBase focuses on short question-based lessons to help researchers get their work done.

- **Purpose:** {{ page.short-purpose }}
- **Who:** {{ page.who }}
- **Maintainer(s):** {{ page.maintainers }}

{{ page.why }}

<strong>Some of the things you will learn include:</strong>
<ul>
	{% for item in page.learn %}
	<li style="font-weight:bold">{{ item|markdownify }}</li>
	{% endfor %}
</ul>

> ## Getting Started
>
> The KnowPulse KnowledgeBase lessons are hands-on, so participants are
> encouraged to use their own computers to ensure the proper setup of tools
> for an efficient workflow. To most effectively use these materials,
> please make sure to download the data and install everything before
> working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the
> workshop.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}


> ## Data
>
> {{ page.data-description }}
{: .prereq}
