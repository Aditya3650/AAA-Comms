---
layout: default
title: Creating Executable Files
nav_order: 3
has_children: false
permalink: /docs/Creating executable files
---

{: .fs-6 .fw-300 }

# Creating Executable Files Using Command Prompt
{: .no_toc }

---

In this section of the guide we will be using Vim (Vi Improved), a screen-based text editor in order to; create C and java files, how to insert code onto such files, how to save them on your computer, and consequently, how to execute the files on your machine.
To downloand the latest version of Vim on your Windows computer visit [here].(https://www.vim.org/download.php)
>**Note:** You must complete Vim installation in order to proceed from this point.

---

### Table of contents
{: .no_toc .text-delta }
* TOC
{:toc}

---

## How to open Vim

Once the installation process is finished:
<br/>
**1.** Using command prompt navigate to the desired folder
<br/>
Image goes here!
<br/>
<br/>
**2.** In order to create your new `.c` or `.java` file write the command `vim` in command prompt.
<br/>
Image goes here!
<br/>
<br/>
**3.** After you type in the command, press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
***Success***

---

## Command Table

Following is a list of command that will be used in this portion of the guide.
<br/>

| Command                           | Description                                                                                             |
| :--------                         | :------------------------------------------------------------------------------------------------------ |
| `vim [fileName].extention`        | Creates `[fileName].extention` if does not exist, and opens `[fileName].extention` for editing.         |
| `:e [fileName]`                   | Opens `[fileName]` for editing.                                                                         |
| `:w`                              | Saves the content written to the file.                                                                  |
| `:sav [fileName].txt`             | Saves the file as `[fileName].txt`                                                                      |
| `:q`                              | Quits Vim.                                                                                              |
| `:q!`                             | Quits Vim without saving.                                                                               |

---

## How To Create A File

There are many several way you can create a new file using Vim. We will focus on the ones we introduced earlier in the command table, namely `vim [fileName].extention` and `:sav [fileName].txt`.
<br/>
<br/>
In order to create the file and name it before putting contents inside of it use `vim [fileName].extention`.
<br/>
<br/>
**1.** After opening command prompt and navgiating to the desired location type in `vim [fileName].extention`.
<br/>
Image goes here!
<br/>
<br/>
**2.** Once you have choosen a file name and the appropriate extention press `Enter` on your keyboard.
<br/>
Image goes here!
<br/>
<br/>
**3.** After pressing `Enter` the Vim editor will open.
<br/>
Image goes here!
<br/>
<br/>
**4.** Press `i` to insert text.
<br/>
Image goes here!
<br/>
<br/>
**5.** To exit insert mode press `Esc`.
<br/>
Image goes here!
<br/>
<br/>
**6.** To save the file and the contents of it type in `:w`, alternatively to quit Vim wihtout saving type in `:q!` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
**7.** In order to quit Vim type in `:q` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
**8.** To compile the source file in `C` or `java`(depending on the language used in the file) type in the compiler name; `gcc [fileName].extention` for `C` or `javac [fileName].extention` for `java`.
<br/>
Image goes here!
<br/>
<br/>
<br/>
The second approach uses Vim interface to save the file after putting all the contents of it first.
<br/>
<br/>
**1.** In the command prompt type in `vim` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
**3.** To exit insert mode press `Esc`.
<br/>
Image goes here!
<br/>
<br/>
**4.** Now, type in `:sav [fileName].extention` to save the file with the given extention and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
**4.** To quit vim type in `:q` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
