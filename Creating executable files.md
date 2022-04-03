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

In this section of the guide we will be using Vim (Vi Improved), a screen-based text editor in order to;
<br/>
**1.** Create `C` and `java` files
<br/>
**2.** How to insert code onto such files
<br/>
**3.** How to save such files on your computer
<br/>
**4.** And consequently, how to execute such files on your machine.
<br/>
<br/>
*To downloand the latest version of Vim on your Windows computer visit [here](https://www.vim.org/download.php).*
>**Note:** You must fully complete Vim installation in order to proceed.

---

### Table of contents
{: .no_toc .text-delta }
* TOC
{:toc}

---

## Useful Commands

The following is a list of commands that will be used in this section.
<br/>

| Command                           | Description                                                                                             |
| :--------                         | :------------------------------------------------------------------------------------------------------ |
| `vim [fileName].extention`        | Creates `[fileName].extention` if does not exist, and opens `[fileName].extention` for editing.         |
| `:e [fileName]`                   | Opens `[fileName]` for editing.                                                                         |
| `:w`                              | Saves the content written to the file.                                                                  |
| `:sav [fileName].txt`             | Saves the file as `[fileName].txt`                                                                      |
| `:q`                              | Quits Vim.                                                                                              |
| `:q!`                             | Quits Vim without saving.                                                                               |

<br/>
>**Note:** Text inside `[]` is optional.
<br/>
>**Note:** `.extention` is optional, however for the purpose of this guide we will use `.java` or `.c`.

---

## How to open Vim

Once the installation process is finished, in order to open Vim:
<br/>
<br/>
**1.** Using command prompt navigate to the desired folder location on your machine
<br/>
Image goes here!
<br/>
<br/>
**2.** Type in `vim`, and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
**3.** After perssing `Enter` the Vim text editor will open.
<br/>
Image goes here!
<br/>
<br/>
***Success***

---
## How To Create A File

There are several way you can create a new file using Vim. We will focus on the ones we introduced earlier in the commands table, namely `vim [fileName].extention` and `:sav [fileName].txt`.
<br/>
<br/>
In order to create the file and name it before putting its contents inside of it, use `vim [fileName].extention`.
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
*For the purpose of this demo we will use `.c` or `.java`*
<br/>
<br/>
**3.** After pressing `Enter` the Vim text editor will open.
<br/>
Image goes here!
<br/>
<br/>
**4.** Press `i` to enter insert mode.
<br/>
Image goes here!
<br/>
<br/>
**5.** To exit insert mode press `Esc`.
<br/>
Image goes here!
<br/>
<br/>
**6.** To save the file and the contents of it, type in `:w`. Alternatively to quit Vim wihtout saving the file, type in `:q!` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
**7.** In order to quit Vim type in `:q` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
***Success***
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
**2.** To enter insert mode press `i`.
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
**5.** To quit vim type in `:q` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
***Success***
<br/>

---

## How To Execute A File

To execute a `.c` file:
<br/>
<br/>
**1.** Type in `gcc -o optional fileName.c` in the command prompt where the `.c` file is located, and press `Enter`. This will create an executable file named `optional`.
<br/>
Image goes here!
<br/>
<br/>
**2.** In order to run the executable file in your machine, in the same directory type in `./optional` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
<br/>
***Success***
<br/>
<br/>
To execute a `.java` file:
<br/>
<br/>
**1.** Type in `javac Optional.java` in the command prompt where the `.java` file is located, and press `Enter`. This will create an executable file with the same name as `Optional.class`.
<br/>
Image goes here!
<br/>
<br/>
**2.** In order to run the executable file in your machine, in the same directory type in `java Optional` and press `Enter`.
<br/>
Image goes here!
<br/>
<br/>
***Success***
