<h1>Aliases for Bash</h1>
<h2>Description</h2>
<p>This repo is for creating a few key shorts and improving the quality of life by speeding up the commands</p>
<h2>Installation</h2>
<p>To install the shortcuts follow these steps:</p>
<ol>
<li>Navigate to your root folder: <code>cd ~</code></li>
<li>Run the command: git clone https://github.com/lhack-jpeg/aliases.git</li>
<li>Check to see if the folder has been copied with: <code>ll</code></li>
<li>Navigate into the alias folder: <code>cd aliases</code></li>
<li>Give the shell script permissions to run: <code>chmod u+x copy_aliases</code></li>
<li>Navigate back to the root folder: <code>cd ~</code></li>
<li>Run the following shell command: <code>source ~/aliases/copy_aliases</code></li>
<li>Check to see your new aliases: <code>alias</code></li>
</ol>
<h3>How to use:</h3>
<h4>gia</h4>
<p>gia is short hand for git add. Used as gia [File]... to add file(s) separately or can be used as gia . to add all files</p>
<h4>gic</h4>
<p>gic is short hand for git commit -m. To use the command follow gic 'Your descriptive commit message'</p>
<h4>gip</h4>
<p>gip is shorthand for git push</p>
<h4>gwb</h4>
<p>gwb is shorthand for git branch -a. This command is meant to show which current branch you are working on</p>
<h4>gis</h4>
<p>gis is shorthand for git status. This shows the current state of which files are up-to-date, changed or untracked.</p>
<h4>gir</h4>
<p>gir is short hand for git rm. To use the command: gir rm [file]</p>
<h4>em</h4>
<p>em is shorthand for emacs. Use the command as: em [file]</p>
<h4>..</h4>
<p>.. is shorthand for cd .. This command will take you into the parent directory</p>
<h4>c</h4>
<p>c is shorthand for clear. This command will clear the current lines in the terminal</p>
<h4>mkdir</h4>
<p>This command shorthand for mkdir -pv. This used the same as mkdir and allows users to create directories and parent directories in one line with a verbose output to show what has been done</p>
<h4>gich</h4>
<p>This command is a shorthand for git checkout. This will make it faster to switch between branches as well as creating new branches by adding the -b after gich. Example; <strong>gich [branch name]</strong> to switch branch, <strong>gich -b [branch name]</strong> creates new branch.</p> 
<h4>sheb</h4>
<p>This command is shorthand for echo '#!/bin/bash >'. To use the command use sheb [filename]</p>
<h4>cc</h4>
<p>This command is shorthand for creating the first 5 lines for a c program using betty styling for comments. Use <strong> cc [filename]</strong> to create the file.</p>
<h4>chux</h4>
<p>This command is a shortand for <strong>chmod u+x</strong>. To use this command, use <strong>chux [filename]</strong></p>
<h4>envb</h4>
<p>This command is a shorthand for creating a bash script that is portable on different *nix systems. To use the command, use <strong>envb [filename]</strong></p>
<h4>gcco</h4>
<p>This command is a shorthand for compiling c files with the holberton options. use <strong> gcco [filename]</strong></p>
