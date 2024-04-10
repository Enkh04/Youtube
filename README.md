Admin@DESKTOP-BP9VF06 MINGW64 ~
$ git clone https://github.com/Enkh04/Youtube.git
Cloning into 'Youtube'...
warning: You appear to have cloned an empty repository.

Admin@DESKTOP-BP9VF06 MINGW64 ~
$ cd youtube

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ ls

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ vim README.md

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ git commit -m "Demo commit message resolve #2"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Admin@DESKTOP-BP9VF06.(none)')

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ git config --global user.email "enkhtsetsegbatkhuyag1@gmail.com"

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ git config --global user.name "Enkhtsetseg7"

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ git commit -m "Demo commit message resolve #2"
[main (root-commit) 54c51e5] Demo commit message resolve #2
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Enkh04/Youtube.git
 * [new branch]      main -> main

Admin@DESKTOP-BP9VF06 MINGW64 ~/youtube (main)
