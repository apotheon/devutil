# Development Utilities

simple tools to make development simple

* denote: wraps Scribble to simplify the CLI for common tasks

* license: downloads one of several licenses from copyfree.org, intended to be
  used to add a LICENSE file to your new software repository

## Usage

Each command line tool should have a `-h` option you can use to learn how to
make use of the tool.

## Installation

Stick the tool you want to use in a directory within your $PATH.  You may need
to use `chmod 700` (if installed per user) or `chmod 755` (if installed
globally) to make it executable.

## Implementation

These tools use sh-compatible scripting and basic Unix utilities.  Some Linux
distributions may not come with standard Unix utilities by default.
Identifying what packages to install to approximate a proper Unix-like
environment is left as an exercise for the user.

## Copyright Concerns

This repository's license terms are in the LICENSE file.  It is intended to be
as widely usable as possible.  If you for some reason cannot legally make use
of this code with current licensing, please file an issue with a desription of
the problem so that can be rectified.

I am unlikely to press any legal issues related to licensing unless you work
for the state, and probably not even then.
