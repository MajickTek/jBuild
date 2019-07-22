# jBuild
Simple build scripts to work with JavaC

# Code
Linux
~~~~SH
$ find -name "*.java" > sources.txt
$ javac @sources.txt
~~~~

Windows
~~~~BAT
> dir /s /B *.java > sources.txt
> javac @sources.txt
~~~~
