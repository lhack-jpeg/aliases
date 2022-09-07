Aliases for Bash
================

Description
-----------

This repo is for creating a few key shorts and improving the quality of life by speeding up the commands

Installation
------------

To install the shortcuts follow these steps:

1.  Navigate to your root folder: `cd ~`
2.  Run the command: git clone https://github.com/lhack-jpeg/aliases.git
3.  Check to see if the folder has been copied with: `ll`
4.  Navigate into the alias folder: `cd aliases`
5.  Give the shell script permissions to run: `chmod u+x copy_aliases`
6.  Navigate back to the root folder: `cd ~`
7.  Run the following shell command: `source ~/aliases/copy_aliases`
8.  Check to see your new aliases: `alias`

### How to use:

#### gia

gia is short hand for git add. Used as gia \[File\]... to add file(s) separately or can be used as gia . to add all files

#### gic

gic is short hand for git commit -m. To use the command follow gic 'Your descriptive commit message'

#### gip

gip is shorthand for git push

#### gipl

gipl is a shorthand for git pull

#### gwb

gwb is shorthand for git branch -a. This command is meant to show which current branch you are working on

#### gis

gis is shorthand for git status. This shows the current state of which files are up-to-date, changed or untracked.

#### gir

gir is short hand for git rm. To use the command: gir rm \[file\]

#### gichb

This command is a shorthand for **git checkout -b** which creates and changes to the branch following the command. E.g **gichb \[branch name\]**.

#### gim

This command is a shorthand for git merge

#### em

em is shorthand for emacs. Use the command as: em \[file\]

#### ..

.. is shorthand for cd .. This command will take you into the parent directory

#### c

c is shorthand for clear. This command will clear the current lines in the terminal

#### mkdir

This command shorthand for mkdir -pv. This used the same as mkdir and allows users to create directories and parent directories in one line with a verbose output to show what has been done

#### gich

This command is a shorthand for git checkout. This will make it faster to switch between branches as well as creating new branches by adding the -b after gich. Example; **gich \[branch name\]** to switch branch, **gich -b \[branch name\]** creates new branch.

#### sheb

This command is shorthand for echo '#!/bin/bash >'. To use the command use sheb \[filename\]

#### ccf

This command is shorthand for creating the first 5 lines for a c program using betty styling for comments. Use **ccf \[filename\]** to create the file.

#### chux

This command is a shortand for **chmod u+x**. To use this command, use **chux \[filename\]**

#### envb

This command is a shorthand for creating a bash script that is portable on different \*nix systems. To use the command, use **envb \[filename\]**

#### gcco

This command is a shorthand for compiling c files with the holberton options. use **gcco \[filename\]**

#### rmf~

This command removes all files ending with '~' in the current directory forcefully.

#### emread

This command creates a README.md file with an empty h1 and a h2 filled out with the author name.

To set the environment variable on a linux machine

`export AUTHOR='YOUR_NAME_HERE'`

#### cim

This command adds **#include \\"main.h\\"** followed by comment starters.

#### em.h

This command creates an empty main.h file with guards.

#### shepy

This command generates a python script with `#!/usr/bin/python3` as the top line
