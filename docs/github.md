---
layout: default
title: Create A Github Repository
nav_order: 3
has_children: false
permalink: /docs/github

---

# Create A Github Repository Using Command Prompt
{: .no_toc }

In this section you will learn basic Git commands, and how to create a Github repository using command prompt. 
<br/>
<br/>
In order to be able to use Github you must first sign up for a Github account. Please refer to the following link to sign up for [Github](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account).
<br/>
<br/>
Once you have signed up for a Github account, you must install Git on your machine. Please refer to the following link to install [Git](https://git-scm.com/downloads).

---

### Table Of Contents
{: .no_toc .text-delta }
* TOC
{:toc}

---

## Useful Commands

>| Command                           | Description                                                                                             |
>| :--------                         | :------------------------------------------------------------------------------------------------------ |
>| `git config --global user.name <Your name here>`| Configures Git on your machine using your name. |
>| `git config --global user.email <your_email@example.com>` | Configures Git on your machine using your email address. |
>| `git config --global -list` | Displays your Git information. |
>| `git add <file name>` | Adds files to the local repository. |
>| `git commit -m"message explaining your intention for making a change"` | Adds a commit message. |
>| `git push` | Pushes the files to cloud. |

---

## How to configure Git On Your Machine

When you have installed Git on your machine you must set it up by entering your credentials. Once you have entered your credentials, an email will be sent to the email account you used to authenticate your identity.
<br/>
<br/>
In order to do the aforementioned tasks please perform the following step:
<br/>
<br/>
**1.** Open Command Prompt.
<br/>
<br/>
**2.** Type the following command to configure your account on your machine.
<br/>
<br/>
>`git config --global user.name <Your name here>`

<br/>
*Image goes here!*
<br/>
<br/>
**3.** Type the command:
<br/>
<br/>
>`git config --global user.email <your_email@example.com>`

<br/>
*Image goes here!*
<br/>
<br/>
**4.** Go to your email account, find the email from Git and authenticate your identity.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
Once you have entered your credentials, you can double check your credentials by typing the following command on Command Prompt:
<br/>
<br/>
>`git config --global -list`

<br/>
<br/>
***Success***

---

## How To Create A Github Repository

In order to create a Github Repository, you must first make a folder/directory that will be used as a Github repository.
<br/>
To create a Github repository do the following steps:
<br/>
<br/>
**1.** Open Command Prompt.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**2.** Navigate to the desired directory where you want to store the Github repository.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**3.** Use the “mkdir” command to create a new folder.
<br/>
<br/>
>`mkdir <file name>`

<br/>
*Image goes here!*
<br/>
<br/>
**4.** Go to the directory you created.
<br/>
<br/>
>`cd <file name>`

<br/>
*Image goes here!*
<br/>
<br/>
Once you are within the directory/folder you created for your Github repository, you must turn that directory into a Github repository. To do so must type command `git init`. When you type the initialize command, the directory you created turns into a Github repository.
<br/>
Inside this new repository, there is a folder named “.git”. This folder stores the internal files and information Git and Github use to function.

**Caution** Do not touch this folder.

---

## How To Push A File To Github

Now that you have a Github repository, you can create new files and folders inside the Github repository, and you can push these files and folders to the Github cloud.  
<br/>
To push a file to the Github cloud you must add that folder to the cache. Then you must commit the content of the cache to the Git version control system with a message. Then you must push the files you committed to the Github cloud. To do the preceding please perform the following steps:
<br/>
<br/>
**1.** Add the file to local repository.
<br/>
<br/>
>`git add <file name>`

<br/>
*Image goes here!*
<br/>
<br/>
**2.** Commit the file.
<br/>
<br/>
>`git commit -m"message explaining your intention for making a change"`

<br/>
*Image goes here!*
<br/>
<br/>
**3.** Push your file to cloud.
<br/>
<br/>
>`git push`

<br/>
*Image goes here!*
<br/>
<br/>
When you perform the following preceding steps, you will be able to view the new files/folders on Github’s server by logging to your Github account through your browser.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>

---

## Conclusion

To conclude, we learned how to interact with Git and Github from CMD. We installed Git and signed up for a Github account. We configured Git by entering our credentials. In addition, we initialized a Git repository. We added files to cache, we committed the files to Git source control and we pushed the files to the Github cloud. Next, we will learn how to use the Vim text editor.
<br/>
<br/>
