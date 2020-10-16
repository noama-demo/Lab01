# Lab-01
## Exercise 1 - Creating your first repository

#### Creating a repo
- Go to a playground folder using explorer (c:\temp, for example)
- Create a new folder named 'my-repo' and enter it
- Right click inside the folder and select 'GitExt create new repository'
- Right click inside the folder and select 'GitExt open repository'
#### Adding files and commits
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
#### Review the commits
- Click on different commits on the graph and experience the:
    1. SplitView - Diff
    2. SplitView - FileTree

## Exercise 2 - cloning a repository
#### Cloning a repo
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL C:\GitServer\labs\Lab01-ex2 and choose clone
- Right click inside/on the folder and select 'GitExt open repository'

#### Adding commits
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
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add any explaining message
    4. Click commit
#### Review the commits
- Click on different commits on the graph and experience the:
    1. SplitView - Diff
    2. SplitView - FileTree

#### Mail the results
- To: <TBD>
- Topic: clone and init
- Body: The commit SHA of the first time ClassA.cs was added
