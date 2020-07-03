# cheatsheets
My personal cheat-sheets to be used with cheat/cheat

## Format
Cheatsheets are plain-text files that begin with an optional "front matter" header in YAML format. The header may be used to assign "tags" to a sheet, and to specify the sheet's syntax (bash, python, go, etc).

When possible, cheatsheets should conform to this format:

<pre>
---
syntax: bash
tags: [ vcs, development ]
---
# To stage all changes in the current directory:
git add --all

# To commit staged changes:
git commit -m <message>
</pre>

As a guideline, it is preferred to use [docopt](http://docopt.org/) syntax when specifying parameter placeholders. In edge-cases where that syntax may cause confusion, it is permissible to use placeholder values (foo.txt, example.com, etc.) as necessary.
