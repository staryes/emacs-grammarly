emacs-grammarly.el --- simple plugin to send a text to Grammarly  
===================================================================================

![](docs/demo.gif)

**From Grammarly then you can copy-paste your text wherever you want (including back to your Emacs).**

Install Grammarly App (OSX version in this case) https://www.grammarly.com/native/mac 

This is a proof of concept. Feel free to send pull requests or fork it.

Read more at https://www.reddit.com/r/emacs/comments/6x0ezx/emacs_grammarly_a_simple_plugin/ 

Install
-------------------------------------------------------------------------------
Insert this code into your `.emacs`:

    # load el file in your .emacs, e.g. 
    (load-file "~/.emacs.d/plugins/emacs-grammarly/emacs-grammarly.el")

Configuration
--------------------------------------------------------------------------------

Change the variables in the `emacs-grammarly.el` file, so it would work for you:

    (defvar grammarly-tempfile "/home/magnus/Desktop/Grammarly.txt")
    (defvar grammarly-cmd "open -a Grammarly")

Change to your tempfile and change a way how you would run Grammarly from the terminal (this way works of OSX).
