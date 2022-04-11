---
layout: default
title: Creating Executable Files
nav_order: 4
has_children: false
permalink: /docs/creatingExecutableFiles

---

{: .fs-6 .fw-300 }

# Creating Executable Files Using Command Prompt
{: .no_toc }

---

As command prompt allows you to accomplish regular tasks on your machine by simply utilizing the keyboard, it is fair to mention that coding is also possible using the command prompt interface. In this section of the guide we will be using Vim (Vi Improved), a screen-based text editor to;
<br/>
<br/>
**1.** Create a `C` or `Java` file
<br/>
**2.** Write code into `.c` or `.java` file
<br/>
**3.** Save a file
<br/>
**4.** And consequently, compile and execute a `.c` or `.java` file on your machine.
<br/>
<br/>
*To download the latest version of Vim on your Windows computer visit [here](https://www.vim.org/download.php).*

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: You must complete installation of Vim text editor on your machine in order to proceed.

---

### Table of contents
{: .no_toc .text-delta }
* TOC
{:toc}

---

## Useful Commands

There are two type of commands that will be used to guide you through this demo. The first catagory of the commands belong to command prompt. The second catagory of command belong to the Vim text editor.
<br/>
<br/>
**1.** The following is a list of command prompt commands that will be used in this section.
<br/>

>| Command                           | Description                                                                                             |
>| :--------                         | :------------------------------------------------------------------------------------------------------ |
>| `vim <file name>.extention`        | Creates `<file name>.extention` if does not exist, and opens `<file name>.extention` for editing.         |
>| `gcc -o <optional> <file name>.c`  | Compiles the file <file name>c` and creates and creates an executable file named `<optional>`.           |
>| `./<optional>`                    | Executes the executable file named `<optional>`.                                                        |
>| `javac [Optional].java`           | Compiles the java file named `[Optional].java` and creates and executable file named `Optional.class`.  |
>| `java [Optional]`                 | Executes the `<Optional>.class` executable file.                                                        |

<br/>
<br/>
**2.** The following is a list of Vim commands that will be used in this section.
<br/>

>| Command                           | Description                                                                                             |
>| :--------                         | :------------------------------------------------------------------------------------------------------ |
>| `:e <file name>`                   | Opens `<file name>` for editing.                                                                         |
>| `:w`                              | Saves the content written to the file.                                                                  |
>| `:sav <file name>.extention`             | Saves the file as `<file name>.extention`.                                                                     |
>| `:q`                              | Quits Vim.                                                                                              |
>| `:q!`                             | Quits Vim without saving.                                                                               |

<br/>

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: The text inside `<...>` is<optional>
<br/>
<br/>
<br/>

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: `.extention` is and example, however for the purpose of this guide we will use `.java` or `.c`.

---

## How to open Vim

Once the installation process is finished, in order to open Vim:
<br/>
<br/>
**1.** Using command prompt navigate to the desired folder location on your machine
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**2.** Type in the following command and press **[Enter]**.
<br/>
<br/>
>`vim`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
At this point, you should be able to see the Vim text editor interface on your command prompt window.
<br/>
<br/>
***Success***

---
## How To Create A File

There are several way you can create a new file using Vim. We will focus on the ones we introduced earlier in the commands table, namely `vim <file name>.extension` and `:sav <file name>.extension`.
<br/>
<br/>
**1.** Type in the following in order to create the file and name it before putting its contents inside of it.
<br/>
<br/>
>`vim <file name>.extension`.

<br/>
<br/>

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: For the purpose of this demo we will use `.c` or `.java`.

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**2.** Once you have choosen a file name and the appropriate extention press **[Enter]** on your keyboard.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
At this point the Vim text editor interface must open in command prompt window.
<br/>
<br/>
**3.** Press **[i]** to enter insert mode.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**4.** To exit insert mode press **[Esc]**.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**5.** Type in the following to save the file and the contents of it.
<br/>
<br/>
>`:w`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**6.** To quit Vim without saving the file, type in the following, and press **[Enter]**.
<br/>
<br/>
>`:q!`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**7.** In order to quit Vim use the following command.
<br/>
<br/>
>`:q`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
***Success***
<br/>
<br/>
The second approach uses Vim interface to save the file after putting all the contents of it first.
<br/>
<br/>
**1.** In the command prompt type in `vim`, and press `Enter`.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**2.** Press **[i]** to enter `insert` mode.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**3.** To exit `insert` mode press *[Esc].
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**4.** Now, type in the following command to save the file with the given extention, and press **[Enter]**.
<br/>
<br/>
>`:sav <file name>.extention`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: We will use `.c` or `.java` for the purpose of this demo.

<br/>
<br/>
**5.** To quit vim type in `:q` and press **[Enter]**.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
***Success***
<br/>

---

## How To Compile And Execute A File

In order to execute a `.c` file:
<br/>
<br/>
**1.** Type the following command in the CMD where the `.c` file is located, and press **[Enter]**.
<br/>
<br/>
>`gcc -o <optional><file name>c`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
This will create an executable file named <optional>.
<br/>
<br/>

**2.** In order to run the executable file in your machine, in the same directory type in the name of the file and press **[Enter]**.
<br/>
<br/>
>`<optional>`.

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
<br/>
***Success***
<br/>
<br/>
To execute a `.java` file:
<br/>
<br/>
**1.** Type in the java compiler name in the command prompt where the `.java` file is located, and press **[Enter]**.
<br/>
<br/>
>`javac Optional.java`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
This will create an executable file with the same named `Optional.class`.
<br/>
<br/>
**2.** In order to run the executable file in your machine, in the same directory type in the following and press **[Enter]**.
<br/>
<br/>
>`java Optional`

<br/>
<br/>
*Image goes here!*
<br/>
<br/>
***Success***

----

## Conclusion

To summarize, we installed Vim, and then we created C or Java file using Vim. We learned what `insert` mode and `control` mode are, and we learned how to use them. We saved the changes and we exited using vim’s control commands.
<br/>
<br/> 
