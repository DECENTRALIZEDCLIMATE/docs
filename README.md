---
title: DOCUMENTS REPOSITORY README
author: Decentralized Climate Foundation
date: 2022-02-04
category: README
layout: post
---

:space_invader:
[![GNUv1.3 License](https://img.shields.io/badge/License-GNU%20v1.3-yellow.svg)](https://opensource.org/licenses/) [![GitHub contributors](https://img.shields.io/github/contributors/decentralizedclimate/docs.svg?style=flat)]() :space_invader:

## :computer:  Introduction :computer:

The purpose of the README is to guide on how to contribute to the DCF 
>And not die in the process.

### System requirements. :card_file_box:

* Knowledge of Git and GitHub.
* Having previously read the Jekyll documentation.
* Basic concepts about IPFS.
* Access to [Fleek](https://fleek.co/) account or creating one.
* You must have installed [Rubygems](https://rubygems.org/pages/download) (check your Gems version using gem -v),[GCC, and Make](https://www.delftstack.com/es/howto/linux/how-to-install-gcc-compiler-on-ubuntu/) (check versions using gcc -v, g++ -v, and make -v), as well as [Ruby 2.5.0](https://www.ruby-lang.org/es/documentation/installation/) (check your Ruby version using ruby -v).

## :scroll: How to contribute to DCF.  :scroll:

### :notebook: "Verify that there are no issues in DCF."  :notebook:

"Verify that there are no issues in DCF that address the contribution or problem you wish to collaborate on (as it may have already been started by another user)."

You can check the issues at the following [**link:**](https://github.com/orgs/DECENTRALIZEDCLIMATE/projects/1)


#### :artificial_satellite:  "How to create a proposal or an issue:" :artificial_satellite:


If you have previously verified that the proposal or issue does not exist, you can write it following the following format:

After accessing the issues link, we must check if there is no related proposal or issue on the list. If we realize that there is none, we can add one by clicking on the **+** sign and assigning a brief title to it.



![](/assets/Readme/p1.png)
**Img1:** At the bottom of the issues, you can add a new one (Remember to check that there is no related open issue and its status).


![](/assets/Readme/p2.png)


---


:eye_speech_bubble: **To create an issue in Github, follow these steps:** :eye_speech_bubble:

1. Access the repository page where you want to create the issue.
2. Click on the "Issues" tab at the top of the page.
3. Click on the green "New issue" button at the top right of the page.
4. Write a brief and descriptive title for the issue in the "Title" field.
5. Describe the problem in detail in the "Write" field.
6. If applicable, use the text formatting options to add formatting, images, or links.
7. Label the issue with appropriate tags to make it easier to find and organize. Tags can be customized by the repository or used from a list of common tags.
8. Assign the issue to a responsible team member or leave it unassigned if not necessary.
9. If applicable, set a due date for the issue.
10. Click the green "Submit new issue" button to publish the issue.

It is important to provide all relevant information so that others can understand the problem and help resolve it. Additionally, it is important to label the issue correctly to make it easier to find and organize. If possible, a proposed solution or suggestions to help solve the problem can also be provided.

---

### :speech_balloon: How to contribute after creating my issue :speech_balloon:

You must clone the [docs](https://github.com/DECENTRALIZEDCLIMATE/docs)  repository to your computer (having the necessary tools and packages to run Jekyll on your computer).


>If you don't have what is necessary to run the repository, you can install what is pertinent for [Jekyll](https://jekyllrb.com/docs/) by clicking on the link.


When you have the repository perfectly installed and configured, you create, improve or solve your issues and send screenshots in the same issue (as responses to it) where we can see the changes and that it works.
>If you need to access the [Issues](https://github.com/orgs/DECENTRALIZEDCLIMATE/projects/1) section of DCF again, you can click on the link.


Send a Pull Request to the Develop branch of DCF docs, filling in the requirements, such as a brief title and comments on what was done. If everything is approved, your issue will be marked as completed and the changes will be added to the project.

#### Suggestions:

>As DCF is a decentralized project, remember that any file, image, or document that you want to contribute needs to have a reasonable size to avoid conflicts when processing it. There are ways to compress it.


## :zap: HOW TO MAKE A POST :zap:
### How to Make a Post in a Jekyll Repository

If you want to publish a post or article on docs.decentralizedclimate.org, follow these steps:

1. Create a markdown file in the following directory if it's for the DCF directory:

```
https://github.com/DECENTRALIZEDCLIMATE/docs/tree/develop/_posts/
or in the following directory if it's for social services:
```

```
https://github.com/DECENTRALIZEDCLIMATE/docs/tree/develop/_posts/socialserv
```

2. The post must contain the following data:
2.1. A header with the following data in markdown format:


```
---
title: Git & Gitflow Cheetsheet EN
author: Decentralized Climate Foundation
date: 2023-03-15
category: git-flow
layout: post
---
```
 2.2. A file name starting with the date in the format YYYY-MM-DD-myposttopic.md. Some examples already exist in the directory.



3. Add a link to the post in the DCF or social services directory by following these steps:
 3.1. For the social services directory, go to the following link and paste the markdown of the post under the "Mans & CheetSheets" section in the following format:

```
## :fire:  Mans & CheetSheets :fire:

| Document | Last Update |
| -------- | -------- |
| [Git & GitFlow ES]({% post_url socialserv/2023-03-15-gitflowCheetSheet_ES %}) |  2023-02-16 |
| [Git & GitFlow EN]({% post_url socialserv/2023-03-15-gitflowCheetSheet_EN %}) |  2023-02-16 |
```


3.2. Similarly, for the DCF directory, add a link with these example directives to the following link:

```
https://github.com/DECENTRALIZEDCLIMATE/docs/blob/develop/index.md
```

>Note that the URL is not a permalink. It is in the format YYYY-MM-DD-myposttopic without the .md extension.


4. Optional: You can fork the project on your user account on the develop branch and link it to hackmd.io to edit before making a commit to your own repository. Then, submit a pull request, or edit the post directly in the GitHub editor.

5. When your request is accepted on the develop branch, it will appear on the following link:

[**develop branch website**](https://develop.docs.decentralizedclimate.org/)

6. Additionally, if you want to add images to your post, place them in the assets directory. Please refer to the README.md for more information.

7. If you have any questions, you can convene a meeting or workshop with the board of directors.



### License. :mechanical_arm:

```
Copyright (C) DECENTRALIZED CLIMATE FOUNDATION A.C.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License". 
```

### Contact: :calling:

[Decentralized Climate Foundation](https://t.me/decentralizedclimate)


### CONTACT AND DEVELOPERS
>Work developed in collaboration with the [Decentralized Climate Foundation](https://decentralizedclimate.org).

Author:
- [Gustavo Bermudez](mailto:nizaries44@gmail.com)		
										  
Reviewer:
- [David E. Perez Negron R.](mailto:david@neetsec.com)





