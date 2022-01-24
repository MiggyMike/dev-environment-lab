![alt text][logo]

[logo]: img/explorerSS.png "Explorer Screenshot"

# dev-environment-lab

## OS

darwin20.1.0

## Shell

/bin/zsh

## zsh location

/usr/local/bin/zsh

## code alias

/usr/local/bin/code

## GitHub CLI version

gh version 2.4.0 (2021-12-21)
https://github.com/cli/cli/releases/tag/v2.4.0

## npm version

8.1.2

## node version

v16.13.2

## nodemon version

2.0.15

## Heroku version

heroku/7.59.2 darwin-x64 node-v12.21.0

## Git version

git version 2.34.1

## Git Default Branch

main

## Git Merge Behavior

## Global Git Ignore

/Users/michaeljennings/.gitignore_global

## Contents of ~/.gitignore_global

# This is a list of rules for ignoring files in every Git repository on your

# computer. See https://help.github.com/articles/ignoring-files

# GitHub maintains a repository of items that can generally be gitignored

# globally safely at: https://github.com/github/gitignore/tree/master/Global

# GitHub also maintains a repository of language-specific items that should

# typically be ignored on a per-project basis with a .gitignore in that

# project's root directory.

# This repository can be found at: https://github.com/github/gitignore

# This file DOES include items that would typically not be gitignored globally

# for simplicity during the course, but this may cause issues as you further

# your education post-SEI. These items are denoted when used here and are kept

# to a minimum.

###############################################################################

# The items in this section are generally safe be globally gitignored and

# are very unlikely to cause projects to break if left here.

###############################################################################

#================================= Archives ==================================#

# Unpack these files and commit the raw source.

# git has its own built in compression methods.

# Compressed Files

_.7z
_.jar
_.rar
_.zip
_.gz
_.gzip
_.tgz
_.bzip
_.bzip2
_.bz2
_.xz
_.lzma
_.cab
_.xar

# Packing-only formats

_.iso
_.tar

# Package management formats

_.dmg
_.xpi
_.gem
_.egg
_.deb
_.rpm
_.msi
_.msix
_.msm
_.msp
\*.txz

#===================== Operating System Generated Files ======================#
#----------------------------------- Linux -----------------------------------#

# Temporary files created as backups by text editors or similar programs

\*~

# Temporary files created if a process is still accessing a deleted file

.fuse_hidden*
.nfs*

# KDE directory preferences

.directory

# Linux trash folder which might appear on any partition or disk

.Trash-\*

#----------------------------------- macOS -----------------------------------#

# General

.DS_Store
.DS_Store?
.AppleDouble
.LSOverride

# Thumbnails

.\_\*

# Files that might appear in the root of a volume

.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share

.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

#---------------------------------- Windows ----------------------------------#

# Windows thumbnail cache files

Thumbs.db
Thumbs.db:encryptable
ehthumbs.db
ehthumbs_vista.db

# Dump file

\*.stackdump

# Folder config file

[Dd]esktop.ini

# Recycle Bin used on file shares

$RECYCLE.BIN/

# Windows shortcuts

\*.lnk

#==================================== Tags ===================================#

# Ignore tags created by etags, ctags, gtags (GNU global) and cscope

tags

#============================ Visual Studio Code =============================#

# .vscode excluding certain .json files

.vscode/\*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json

# Local History for Visual Studio Code

.history/

###############################################################################

# The items in this section may not typically be gitignored globally and

# may cause future projects to break if left here.

# ** However, if you remove them from here, you MUST add them back to the **

# ** projects they apply to by placing a .gitignore containing the items **

# ** to be gitignored in each project's root directory. **

###############################################################################

#=========================== Compiled Source Code ============================#

# Class Files

\*.class

# Dynamic Libraries

_.so
_.dylib
\*.dll

# Executables

_.com
_.exe
_.out
_.app

# Object Files

_.slo
_.lo
_.o
_.obj

#================================== Django ===================================#

# Logs

\*.log

# Local django settings

local_settings.py

# SQL database

db.sqlite3
db.sqlite3-journal

#============================== Node and Python ==============================#

# Environment variables

.env

#=================================== Node ====================================#

# Dependencies

node_modules

#================================== Python ===================================#

# Byte-compiled

\*.py[cd]
**pycache**/
.python-version

#================================== React ====================================#
.eslintcache

# ==================================

# =================================

# =================================

# ================================= OLD SETUP IS BELOW HERE ====================================

# =================================

# =================================

# =================================#

# # This is a list of rules for ignoring files in every Git repositories on your computer.

# # See https://help.github.com/articles/ignoring-files

# # Compiled source

#

# \*.class

# \*.com

# \*.dll

# \*.exe

# \*.o

# \*.so

# # Packages

#

# # it's better to unpack these files and commit the raw source

# # git has its own built in compression methods

# \*.7z

# \*.dmg

# \*.gz

# \*.iso

# \*.jar

# \*.rar

# \*.tar

# \*.zip

# # Logs and databases

#

# \*.log

# # OS generated files

#

# .\_\*

# .DS_Store

# .DS_Store?

# .Spotlight-V100

# .Trashes

# ehthumbs.db

# Thumbs.db

# # Testing

#

# .rspec

# capybara-\*.html

# coverage

# pickle-email-\*.html

# rerun.txt

# spec/reports

# spec/tmp

# test/tmp

# test/version_tmp

# # node

#

# node_modules

# # Rails

#

# \*\*.orig

# \*.rbc

# \*.sassc

# .project

# .rvmrc

# .sass-cache

# /.bundle

# /db/\*.sqlite3

# /log/\*

# /public/system/\*

# /tmp/\*

# /vendor/bundle

# # Ruby

#

# \*.gem

# \*.rbc

# .bundle

# .config

# .yardoc

# \_yardoc

# doc/

# InstalledFiles

# lib/bundler/man

# pkg

# rdoc

# tmp

# # for a library or gem, you might want to ignore these files since the code is

# # intended to run in multiple environments; otherwise, check them in:

# # Gemfile.lock

# # .ruby-version

# # .ruby-gemset

# # CTags

#

# tags

# # Env

#

# .env

# # Python

#

# \*.pyc

# **pycache**/
