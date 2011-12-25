Alot is a terminal interface for [notmuch mail][notmuch] written in 
python using the [urwid][urwid] toolkit.

The files `INSTALL.md` and `CUSTOMIZE.md` contain instructions on how to set it
up and customize respectively.

Autogenerated API docs for the current release can be found [here][api].
Their sources live in the `docs` directory.

The current top-notch version for the courageous lives in branch 'testing'.

Do comment on the code or file issues! I'm curious what you think of it.
You can talk to me in #notmuch@Freenode.

Current features include:
-------------------------
 * modular and command prompt driven interface
 * tab completion and usage help for all commands
 * contacts completion using customizable `abook` lookups
 * user configurable keyboard maps
 * spawn terminals for asynchronous editing of mails
 * theming, optionally in 2, 16 or 256 colours
 * tag specific theming and tag string translation
 * (python) hooks to react on events and do custom formating
 * python shell for introspection
 * forward/reply/group-reply of emails
 * printing/piping of mails and threads
 * multiple accounts for sending mails via sendmail
 * notification popups with priorities
 * database manager that manages a write queue to the notmuch index

Soonish to be addressed non-features:
-------------------------------------
 * encryption/decryption for messages (see branch `gnupg`)
 * live search results (branch `live`)
 * search for message (branch `messagesmode`)
 * bind sequences of keypresses to commands (branch `multiinput`)
 * search for strings in displayed buffer
 * folding for message parts
 * undo for commands


Usage
=====
In all views, arrows, page-up/down, `j`,`k` and `Space` can be used to move the focus.
`Escape` cancels prompts and `Enter` selects. Hit `:` at any time and type in commands
to the prompt.
Usage information on any command can be listed by typing `help YOURCOMMAND` to the prompt;
The keybindings for the current mode are listet upon pressing `?`.


[notmuch]: http://notmuchmail.org/
[urwid]: http://excess.org/urwid/
[api]: http://alot.rtfd.org
[wiki]: https://github.com/pazz/alot/wiki
