emacs-clojure
=============

Configuration files and other goodies for a Clojure development environment based on Emacs.

* For Ubuntu 12.04, I had to [use a PPA to get emacs 24](https://launchpad.net/~cassou/+archive/emacs)
* Followed directions [clojure-doc.org](http://clojure-doc.org/articles/tutorials/emacs.html) to get everything loaded
* Rememember to soft-link the *.emacs.d* directory from your home directory.

Sample instructions from **Web Development with Clojure**:

1 open guestbook/src/guestbook/repl.clj vi C-x C-f (assumes a previously generated Leiningen project named guestbook).
2 with the repl.clf buffer selected run M-x nrepl-jack-in to start the repl.
3 run  C-c M-n to switch the REPL namespace to our buffer’s.
4 run C-c C-k  to evaluate the buffer.

I was able to start the repl fine but couldn't tell if the namespace switching was working or not.

Sample instructions from **clojure-doc.org**: 

1 M-x package-list-packages to see what other packages are available to verify packages are available.
2 create a Leiningen project named command-line and cd into the directory
3 M-x cider-jack-in to start a reple (notice that they use cider but the book uses nrepl).
4 Follow the instructions to the letter (too many to enumerate here).

I was able to get the compilation to run but the tests never failed as expected.  I'll try again sometime later.  Maybe it
is Light Table for me. <grin>
