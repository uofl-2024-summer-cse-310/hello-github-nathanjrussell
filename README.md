# Hello Github Assignment

Version control is a critical component of engineering and Git is typically one of the core components. Git commands are traditionally executed from the command line.  However, several IDEs (e.g. VSCode, IntelliJ) integrate Git as a graphical interface. Engineers are often make changes simultaneously to project files.  Git is a fundamental tool that helps keep project file changes synchronized.  Below is the general idea.

* A repository is a central storage location for the source files of a project. There is usally a hidden directory (e.g. `.git`) that git software uses to track changes.
* In order to make changes to the source code files, an engineer must bring the most recent changes to their local environment (e.g. laptop).  Git makes this easy using the `clone` command.
* The engineer will make changes to a source code file. 
    * As changes are made, the engineer will stage changes using the `add` command.
    * Once a collection of changes represent stable point, the engineer will commit the staged changes using `commit`.
    * The engineer must eventually make the local changes part of the central repository.  The engineer will `push` the commited changes to the repo for colleagues to review and use.

If you intend on being an engineer...then you MUST learn Git. This can give you a significant bump during a job interview. Solid understanding of git will demonstrate software development maturity. Git has tons of featues but we will only use a few for this course.

# Product Owner Statement

As a computer science instructor I need to evaluate your ability to use Git technology.

The text file `data_primary.json` contains errors that need to be corrected.  Also, the file needs to renamed.

## Acceptance 
The following conditions must be met to earn full credit for this assignment.

* The file `data_primary.json` needs to be renamed to `data.json`.
* The file `data.json` needs to be updated to look like the following JSON object:
```
{
    "firstName": "Sam",
    "lastName": "Smith",
    "isActive" : "true",
    "idNumber" : "778645",
    "comments" : "New hire in the engineering department",
    "affiliates" : [
        {
            "firstName" : "Jane",
            "lastName" : "Doe",
            "relationship" : "Friend"
        },
        {
            "firstName" : "John",
            "lastName" : "Doe",
            "relationship" : "Neighbor"
        }
    ],
    "officeBuilding" : "Duthie Center For Engineering",
    "officeNumber" : "216"
}

```

## Grading
This assignment is worth 100 points.  No partial credit will be awarded.  All GitHub workflow tests must pass to earn credit. 