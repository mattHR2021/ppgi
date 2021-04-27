# Pair Programming Git Init (ppgi)

## Install
1. cd the to base directory you want to clone the repo to, then
2.     git clone https://github.com/mattHR2021/ppgi.git
3.     cd ppgi
4.     chmod +x ppgi
5.     ./ppgi

asciinema demos:

## Features
+ main feature: automates the git initialization process for HR pair programming
  + presents list of HR repos to select from
    + forks selected repo to your GitHub account
    + clones selected repo to your designated HR directory
    + adds HR's repo as remote upstream
    + adds pair's fork as remote
    + exits at the installed repo's basedir
+ bonus features:
  + installs ppgi to your $PATH so you can use it from anywhere in your shell
  + stores you GH UserName
  + stores your preferred HR directory
  + adds an optional 'pomander' alias - installs pomander at $PWD
  + adds an optional 'cdh' alias - cd's to your HR dir

## Uninstall
    ./ppgi uninstall

### To-Do
+ rewrite in POSIX sh
