# Lab-01
## Exercise 1 - Creating your first repository
### Overview
In this exercise, we will create our first new repository using gitextensions  
This is similar to git init command  

#### <u> Creating a repo </u>
- Go to a playground folder using explorer (c:\temp, for example)
- Create a new folder named 'Lab01-ex1' and enter it
- Right click the folder and select 'GitExt create new repository', click 'Create' and 'Ok'
- Right click in the folder and select 'GitExt open repository'
#### <u> Adding files and commits </u>
- Tip: You can use the File Explorer button on the Button Bar to open explorer
- Create 3 files in your new folder (using notepad, or any other editor)
    - file1.txt
    - file2.txt
    - file3.txt
- Commit file1.txt
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add message "adding files" (you can name them)
    4. Click commit
- Commit file2.txt, file3.txt
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add message "adding files" (you can name them)
    4. Click commit
#### <u> Review the commits</u>
- Click on different commits on the graph and experience the:
    1. SplitView - Diff
    2. SplitView - FileTree

## Exercise 2 - cloning a repository
### Overview
In this exercise, we will clone a repository using gitextensions  
This is similar to git clone command  

#### <u> Cloning a repo </u>
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL C:\GitServer\labs\Lab01-ex2 and choose clone
- Right click in the folder and select 'GitExt open repository'

#### <u> Adding commits </u>
- <b>Tip</b>: You can use the File Explorer button on the Button Bar to open explorer
- Modify gitDemo\ClassA.cs
- Add the following comment to line 6
    ```
    // comment to commit
    ```
- Modify gitDemo\ClassB.cs
- Add the following comment to line 6
    ```
    // comment to commit
    ```
- Commit both files
- Commit:
    1. On the Button Bar, Press the Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add any explaining message
    4. Click commit
#### <u> Review the commits </u>
- Click on different commits on the graph and experience the:
    1. SplitView - Diff
    2. SplitView - FileTree

#### <u> Mail the results </u>
- To: <TBD>
- Topic: clone and init
- Body: The commit SHA of the first time ClassA.cs was added
