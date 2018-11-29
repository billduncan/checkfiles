# checkfiles

## Created
   bduncan@beachnet.org, Sun Jan  7 17:17:38 EST 2018

## Description
- see the description here:  https://billduncan.org/bitrot-part-2
- create, maintain and check files against an .md5 file in base of specified directories.
- if no .md5 file exists, create one
- check files against existing .md5 file and report differences.
- a log kept as well in .md5.log

## It Finds and Reports on
- changed files
- added files
- deleted files
- and makes suggestions about it being moved if it finds files with same md5

## Use For
- comparing after a period of time to check for changes
- compare directories that are supposed to be equivalent (eg. across systems, backups, archives)
- finding duplicate files

## Usage
```
  checkfiles [-options] directory [directory..]
  options:
    -h     print help and exit
    -q     quiet
    -n n   nice value
    
```

