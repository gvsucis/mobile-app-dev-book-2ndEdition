# mobile-app-dev-book-2ndEdition

This is the parent repo of all sample code from the Engelsma &amp; Dulimarta text book on mobile app development (2nd edition).  It references two separate
GitHub repos containing the iOS and Android code from the book:

* https://github.com/gvsucis/mobile-app-dev-book-android
* https://github.com/gvsucis/mobile-app-dev-book-iOS

You can clone all the sample code for the book with this single command: 

    git clone --recurse-submodules https://github.com/gvsucis/mobile-app-dev-book-2ndEdition
    
The book incrementally creates the Traxy app - a multimedia travel journaling app.  Each chapter of the book demonstrates various aspects of the iOS / Android 
frameworks by incrementally introducing new features to the Traxy app,  A each of the repos, a git branch has been created which serves as a snapshot of the 
source code at the end of the chapter.  For example, the branch 'ch02' is a snapshot of the code at the completion of chapter 2.   If you would like a snapshot of
the code at the beginning of a given chapter, simply checkout the branch for the previous chapter.  For example, if you were going to read through Chapter 6 
and apply the code changes as you go, you could start by checking out the branch ch05. 

In order to view the code for a specific chapter, simply cd into the respective subdirectory, and checkout that branch.  For example, if you want to see the 
Android code for Chapter 4, you would execute the following commands on your terminal window (assuming you are in the top level directory of the parent repo):

    cd mobile-app-dev-book-android
    git checkout ch04
    
If you would like to report any errata in the book or source code, simply open an issue in the GitHub issue database of this repository.  

