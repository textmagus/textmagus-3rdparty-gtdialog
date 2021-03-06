# gtDialog

## Overview

gtDialog is a cross-platform application for creating interactive dialogs from
the command line or programmatically. It is written completely in C and can
display graphical dialogs using [GTK+ 2.0][] or terminal-based dialogs using
a curses implementation like [ncurses][]. gtDialog is based on [cocoaDialog][]
and shares many of its dialog types and arguments.

You can use gtDialog as either a standalone command-line program for shell
scripts or a C library for applications in order to easily create interactive
dialogs for yes/no confirmations, textual input, file selections, selection
lists and more.

[GTK+ 2.0]: http://gtk.org
[ncurses]: http://invisible-island.net/ncurses/ncurses.html
[cocoaDialog]: http://cocoadialog.sf.net

## Features

* Graphical (GTK) or terminal-based (curses) dialogs.
* 14 different dialog types including:
  + Messageboxes
  + Inputboxes
  + File selections
  + Textbox
  + Progressbar
  + Dropdown lists
  + Filtered lists
* No knowledge of GTK or curses is required to use either the command-line
  program or C library.
* Any programming language with shell access can utilize the command-line
  program.

## Requirements

gtDialog only requires GTK+ version 2.16 or higher or a curses implementation
and [CDK][].

[CDK]: http://invisible-island.net/cdk/

## Download

Download gtDialog from the project's [download page][] or from this quick link:

* [Source][]

If necessary, you can obtain PGP signatures from the [download page][] along
with a public key in order to verify download integrity. For example on Linux,
after importing the public key via `gpg --import foicica.pgp` and downloading
the appropriate signature, run `gpg --verify [signature]`.

[download page]: http://foicica.com/gtdialog/download
[Source]: download/gtdialog_LATEST.zip

## Installation and Usage

gtDialog comes with a manual in the *doc/* directory. It is also available
[online][].

[online]: http://foicica.com/gtdialog

## Contact

Contact me by email: mitchell.att.foicica.com.

There is also a [mailing list][].

[mailing list]: http://foicica.com/lists
