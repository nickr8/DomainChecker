### What does it do?

The 'registered' bash file makes it possible to check lots of domain names for their availability.

### How to use it:

First of all you create regular .txt file and add all domains that you can think of that you would like to find out if they are available or not.

Then you go into the folder DomainChecker in the terminal and type: ./registered yourfile.txt

The script will run for a little while (depending on how many sites you put in) and then output the names of the sites and say if they are taken or still available. When the script is finished it will also create a file which is named yourfile.txt.free. This file will contain all the urls from your original textfile that are still available.

Have fun!

WARNING: the script is not 100% reliable. In some cases sites are shown as free, although they are already registered. This doesn't happen in most cases but it is possible.