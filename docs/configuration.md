---
layout: default
title: Navigate Through Windows File System
nav_order: 2
---

# Navigate Through Windows File System
{: .no_toc }

In this section you will be introduced to the concept of file system and how Windows file system is structured. Then you will learn how to use command prompt to interact with Windows File System. 

A file system specifies how files and folders are stored and retrieved from a storage device such as a hard drive or a solid state drive. Different operating systems use different file systems. That is, a file system on a windows machine is different from a file system on a MacBook. In this guide, we will explain the file system structure on Windows operating system, and how command prompt can be used to interact with Windows operating system.

---

### Table Of Contents
{: .no_toc .text-delta }
* TOC
{:toc}

---

## Useful Commands

>| Command                           | Description                                                                                             |
>| :--------                         | :------------------------------------------------------------------------------------------------------ |
>| `tobeadded`                       | ...                                                                                                     |
>| `tobeadded`                       | ...                                                                                                     |
>| `tobeadded`                       | ...                                                                                                     |
>| `tobeadded`                       | ...                                                                                                     |
>| `tobeadded`                       | ...                                                                                                     |

---

## Explanation Of Absolute And Relative Path
To begin with, Windows uses a hierarchical file system structure. That is, various folders/directories nested within other folders/directories. The folder that is on the top of the hierarchy is called the root folder. The root folder on Windows is called “C” directory. This directory is the highest directory and contains other folders and files on Windows. 

C directory contains files and folders that windows uses to function. Deleting or altering the aforementioned files and directories may cause the operating system to crash and result in a total data loss. So C directory is not a directory to mess around with. 

C directory also contains a folder called “Users”. “Users” folder contains the user accounts on your computer. These user accounts are stored as folders. Each of these User account folders contains the files and folders that casual users use to interact with Windows. These folders include  Desktop folder, Downloads folder, Documents folder and Pictures.

Windows uses a thing called a path to indicate the hierarchical relationship between various directories. A path indicates where a folder is stored with respect to another directory that is higher up the hierarchy. In other words, a path indicates how many levels below a higher directory a lower directory is stored. See the following for an example of a path:

*`C:\Users\tom\Desktop`

The preceding path indicates that there is a folder called “Users” within a folder called “C”. And that there is a folder called “tom” within the “Users” folder, and that there is a folder called “Desktop” within the “tom” folder. As you can see, there is a hierarchical relationship between these folders in the path. That is, these folders are nested within each other. 

There are two types of paths on Windows. Absolute path and relative path. The preceding path shown is an example of an absolute path. An absolute path specifies a folder’s location with respect to the root directory or the C directory.

On the other hand, a relative path specifies the path with respect to some other directory higher up the hierarchy but not the root directory. That is, if two directories are stored within the same directory and we want to go from the first directory to the second directory, we do not have to necessarily provide the absolute path of the second directory. We can just provide the relative path to the directory that contains these two directories to switch to the second directory.   

Now that you have understood the file system structure on Windows, you will be introduced to Command Prompt commands that can be used to navigate through Windows’ file system.

---

## Handling Files Using Command Prompt

We will begin by creating a directory and then we will create a text file within the directory in question. Then we will add a sentence to that text file and then we will rename the text file. Then we will create another directory and then we will move the text file to the second directory we created. In order to do the preceding please perform the following steps: 
**1.** Open command Prompt.
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**2.** Once you open the command prompt you must specify the directory where you wish to create your customized directory in. In other words, you must specify the parent directory that will contain your directory. To do so you must enter the “change directory” command followed by either the full path or the relative path to the parent directory.
<br/>
<br/>
`cd <absolute or relative path>`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**3.** Create another directory by typing the “make directory” command followed by the name of the directory.
<br/>
<br/>
`mkdir <directory name>`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**4.** Move within the directory by typing “change directory” command followed by the name of the directory.
<br/>
<br/>
`cd <directory name>`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
**5.** Create a text file. To do so you must type the “touch” command followed by the name of the file and then the file extension which is in our case a “.txt” file extension. 
<br/>
<br/>
`touch <file name>.txt`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
When you have created the text file, you can add some content to your file by opening the file with Windows default text editor “notepad”.
<br/>
<br/>
**6.** Type the “notepad” command followed by the name of the file and the file’s extension(a file’s full name is the actual name of the file followed by its file extension). When you type the notepad command, the notepad text editor opens up and you can add content to your file. Be sure to save the changes you added to the text file and then close the notepad text editor.
<br/>
<br/>
`notepad <file name followed by file’s extension>`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
Now that you have created a text file with some content inside it.
<br/>
<br/>
**7.** Rename the text file. To do so type the “rename” command followed by the full name of the file(a file name followed by its extension) you want to rename followed by the new name of the file followed by the file’s extension. 
<br/>
<br/>
`rename <full file name> <new file name followed by file’s extension>`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
Now that we have renamed our text file, we must create another directory and then move the text file to the new directory.
<br/>
<br/>
**8.** Create the new directory within the current directory we are in. 
<br/>
<br/>
`mkdir <new directory name>`
<br/>
<br/>
*Image goes here!*
<br/>
<br/>
Then we will copy the text file to the new directory we created.
<br/>
<br/>
**9.** Copy the text file name followed by the relative or absolute path to the new directory.
<br/>
<br/>
`move <file full name> <relative or absolute path of the new directory>`
<br/>
<br/>
***Success***

---

## Conclusion

To sum up, we learned about Windows hierarchical file system structure, and we learned the commands that are used to navigate through this file system. We learned how to make a directory, how to create a text file, how to open a text file, and how to move files into different directories.
<br/>
<br/>
Next we will learn how to use CMD to interact with Git and Github.
<br/>
<br/>
