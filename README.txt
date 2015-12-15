pikkuwiki.vim - Vim plugin for pikkuwiki
========================================

Pikkuwiki is a tool for managing a personal wiki.
It's goal is to be simple, minimal, and portable.
This plugin provides some helpful editing and browsing features for pikkuwiki.


Installing
==========

First, make sure you have installed pikkuwiki first.
Instructions for installing pikkuwiki can be found from it's homepage:

  https://github.com/Lepovirta/pikkuwiki

After you've installed and set up pikkuwiki, you can install the Vim plugin.
The easiest set up can be achieved using one of the Vim plugin managers:

  * vim-plug: https://github.com/junegunn/vim-plug
  * Vundle: https://github.com/VundleVim/Vundle.vim

For vim-plug, add the following line to your plugin list:

  Plug 'Lepovirta/pikkuwiki.vim'

For Vundle, add the following line to your plugin list:

  Plugin 'Lepovirta/pikkuwiki.vim'


Usage
=====

Vim plugin provides syntax highlighting and commands for pikkuwiki pages.

The following commands are available:

  :PWOpen     Used for opening links under the cursor.
              An optional link can be supplied as a parameter to jump to an
              arbitrary page.

  :PWFind     Used for finding pages in the pikkuwiki directory.
              Filter parameter can be supplied to filter the pages.

  :PWShow     Used for finding links in the current page.
              Only available in pikkuwiki pages.
              Filter parameter can be supplied to filter links.

The following key bindings are available in pikkuwiki pages:

  gl          Opens the link under the cursor.

The following key bindings are available in pikkuwiki search window:

  <Return>    Opens the link under the cursor.


License
=======

(The MIT license)

Copyright (c) 2015 Jaakko Pallari


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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

