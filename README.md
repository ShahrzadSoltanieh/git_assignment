# Git Assignment - ShahrzadSoltanieh

    a. What is an issue?
        GitHub issues are for planning and keeping track of your work across multiple repositories. You can open issues, assign labels, and assign people to resolve the issues for example reporting bugs and requesting features. you can also give or receive feedback and efficiently communicate and collaborate with others in your project team.

    b. What is a pull request?
        It is essentially a request to merge a change or a set of changes that is made in a seperate branch into another branch which is in most cases is the main branch.

    c. How do I open up a pull request?
        After making the changes and pushing them to a branch of a forked or newly created repository, you need to go to your repository on GitHub, click on the "Pull requests" tab. Then click on the "New" button. GitHub will compare the changes in your branch with the original repository's main branch (base: main <-- compare: assignment). If everything looks good and you are confident with your changes, you can submit the pull request by clicking the "Create pull request".
        Next, you need to provide a complete and clear description of your changes in the pull request to help project team members understand the intention and extent of your proposed changes. Once the pull request is open, team members can review your changes,  ask questions, suggest modifications, and/or approve your pull request. 

    d. Give me a step by step guide on how to add someone to your repository.
        1. Navigate to the repository that you want to add project team members.
        2. Click on the "Settings" tab located on the right side of the repository's menu.
        3. Click on the "Collaborators" section under the Access section (top left).
        4. Navigate to "Manage access", and click on "Add people", you will see a field to invite collaborators by searching their GitHub username, full name, or email.
        5. Once you find the the collaborator's username/full name/ email.
        6. Click on "Add "username" to this repository.
        7. Select the appropriate access level for the collaborator (Read, Write, and Admin) 
        8. Send the invitation.

    e. What is the difference between git and GitHub?
        Git is a version control system used to track changes in files during software development. It operates locally on your computer.
        GitHub is a web-based platform that stores Git repositories in the cloud and provides collaboration tools like issue tracking, project management, and code review.

    f. What does git diff do?
        "git diff" is a Git command used to display what's changed in your code over time. It displays the differences between various states of a Git repository. It's particularly useful for comparing changes between different commits, branches, or the working directory.

    g. What is the main branch?
        The main branch is the default and primary branch in a Git repository, that represents the main line of development. It is where the latest and stable version of the code is maintained, and where all changes from different branches come together and integrated.
        
    h. Besides our initial commit if it is a new repository, should we directly push our    changes directly into the main branch?
        Since the main branch represents the main line of development, and it maintains the stable version of the code, it is not recommended to push changes directly to the main branch, especially in collaborative projects. Directly pushing changes to it without thorough testing can introduce bugs or instability to the codebase.
