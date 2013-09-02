fcd
===

This little command line script allows you to easily switch to a directory starting at the current directory.   What is so magical about this command?  Well it can be nested very deep from your current location.    The "find" command is utilized so any wild card matching that you can do in find you can do with fcd.

If multiple matches are found you will be prompted with a list and you can choose which one you really meant.

Setup
==
Since this script changes to a directory you need to execute it within your current shell via "."   This can be a little bit of pain to do all the time or you may simply forget and and think the script is no working.  So its best to setup an alias like:

```shell
alias fcd='. fcd'
```

Usage
====
. fcd [directory] pattern

Examples
====
```shell
. fcd src
. fcd proje*
```

