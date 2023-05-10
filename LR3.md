Lab Report 3 - Researching Commands
===

Four Intresting Command Line operations for `find` using directory `technical`

IMPOTRANT INFO: `grep` is command line operation that searches for files in a specific directory

---

**First interesting command-line option**
---

`find ~ -type f`

>This command operation will display files, directories, symlinks, named pipes, sockets, and more using the -type option, which is very useful when wanting to view all the files or directories listed in the directory.
>this would be the following command typed on the terminal:
>
>![Image](first.png)
>
>Once you have entered the following command it will print all the files and directories etc.
>
>![Image](firsto.png)
>




**Using the same command but having a specific file type: `find technical -type f,l -name "Fire*"`**

>This is how it would look typed in the terminal: 
>
>![Image](fire.png)
>
>This command version of find, you can include multiple file types in your search results, which will be helpful in finding a specific file in the directory just by adding the name of th specific file trying to find by using `-name "THE TITLE TRYING TO FIND*"` This command will by directly provide all the possible files with the name implemented
>For Examples the command will look somethhing like this if it found a file with the name I implemented (which in this case it was fire):
>
>![Image](fireo.png)
>

**Second interesting command line option**
---

`find technical/(directory)`

>This command can be implemented with the file technical and any choice of directory that you know is present in the file
>One directory that I know is there would be `plos`
>
>In this case I will write in the terminal something like this with the command:
>
>![Image](plos.png)
>
>The reason why this command can be helpful when wanting to see a specific directory and what is inside it. For this command it will output whats inside the specific directory I typed (which in this case is `plos` this:
>
>![Image](ploso.png)
>

**Using the same command but having a different directory implemented: `biomed`**

>Same command will be implemented in the terminal just different directoy:
>
>![Image](biomed.png)
>
>This command will be able to show everything that is placed inside the. `biomed` directory
>Which will output something like this:
>
>![Image](biomedo.png)
>

**Third intresting command line option**
---

`find technical -name "title of file that ends with"`

>This command will be able to find all the files that end with the string implemented in qoutes at the end. In this case will will be using star in front of the last numbers to easily find all the files that end with that number of pair. (* will fill out whatever could possibly be in the front of the pair numbers)
>
>For example in the terminal it will look like this:
>
>![Image](o.png)
>This command is useful to easily find a file by condensing all the possible files that have the string.
>This would be the output of the command:
>
>![Image](o.png)
>

**Using the same command but a diffrenet string implemented at the end to find**

>For this command I will be adding the string `find technical -name ""`
>It will look something like this:
>
>![Image](o.png)
>
>which will provide this output like the example above:
>
>![Image](o.png)
>

**Fourth intresting command line option**
---

`
