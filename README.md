# jBuild
Simple build scripts to work with JavaC

# Code

First all .java files are located and put into a list called sources.txt.

Then javac is called to compile sources.txt. So simple that the scripts are given below as well as in the src folder of the repo.


## Linux
~~~~SH
$ find -name "*.java" > sources.txt
$ javac @sources.txt
~~~~

## Windows
~~~~BAT
> dir /s /B *.java > sources.txt
> javac @sources.txt
~~~~
