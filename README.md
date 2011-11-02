# git status monitor and utilities for bash

<pre>
                /==> Username                 /=> Current Path
               /                             /
[master] patricknegri@~/Desenvolvimento/os/arcabouco-js:
   \
    \==> Name of git repository, also RED if repository is changed, GREEN if its commited
</pre>

# Installation

<pre>
Save .git-bash-status to your home directory or env
Edit your .bash_profile, and put at end
source ~/.git-status.bash
Reopen your bash / terminal

PLUS: For MAC Osx users, GIT Bash Autocompletion
source ~/.git-completion.bash
</pre>

# Provided Alias

<pre>
  ..  => cd ..
  ls  => ls -F
   l  => ls -A
  gl  => git pull
  gp  => git push
  gd  => git diff
gpom  => git push origin master
  gc  => git commit
 gco  => git checkout
 gca  => git commit -a
  gb  => git branch
  gs  => git status
 grm  => git status | grep deleted | awk '{print \$3}' | xargs git rm
pull  => git pull origin master
</pre>

# LICENSE

Copyright (C) 2011 by Patrick Negri

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
