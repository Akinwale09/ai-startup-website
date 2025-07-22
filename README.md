# ai-startup-website
## Hands-On Git Project: Collaborative Website Development with Git and GitHub

In this mini project, I will crate a step by step project to simulate the workflow of Tom and Jerry using Git and GitHub. This hands-on project will include installation of Git, setting up GitHub repository, creating branches, making changes, and merging those changes back into the main branch. 

## Part 1

1. Install Git: 

   - Visit the office git website and downlaod (https://git-scm.com/downloads) the version of Git for your operating system. Folow the installtion instruction. 
2. Create a GitHub Repository:

    - Sign up or login into GitHub
    - Click the "+" icon in the top-right corner and select "New Repository".
 
       ![CreateRepo](./img/1.createRepo.png)
   

     - I would create my Repository and name my project ai-startup-website and initialize it with a README file

         ![creatingRepo](./img/2.creatingRepo.png)
        

3. Clone the Repository
   
    - On the repository's page on GitHub, click the code button and copy the HTTPS URL

       ![cloning Repo](./img/3.cloningRepo.png)
    
    - I will now open git on my pc which I already created a folder in my PC with git-project, I will do `cd` to this folder directory.

       ![cdtoprojectfolder](./img/4.cdtoGitProject.png)
    - Clone the (Downlaod) the repository from GitHub using `git clone` 
  
       ![clone](./img/5.ProjectClone.png)

    - The project has been successfully clone to my local maching and `cd` to ai-startup-website folder

        ![cdtothefolder](./img/6.cd-to-ai-project.png)

     - create a file index.html with `touch index.html`
  
         ![htmlfile](./img/7.index-htmlfile-created.png)

     - Add a content into the file using `vi` editor

       ![content](./img/8.html-content-created.png)


     - `cat` use cat to check the file is successfully saved

       ![savedfile](./img/9.cat-to-check-the-content.png)

    - Check the change has not been change with 
  
      `git status`

      ![statu](./img/10.git-status.png)

     - Stage chnages with: `git add index.html`

       ![gitadd](./img/11.gitaddindexhtml.png)

    - Confirm the changes have been staged fro commit with `git status`

        ![statusagain](./img/12.statuschangetogreen.png)

     - Now, after staging the changes, the file will appear in green in the terminal output. This color shange signifies that the file has been successfully staged, making it ready for the next step, which is commiting these changes to the project history. 

      - Commit the th change with `git commit -m "message"`
     
    ![commit](./img/13,gitcommit.png)

    - This takes the staged changes and records them in the repository's history with a message describing what was done. 

    - Push the main branch to GibHub: using `git push origin main`

     ![push](./img/14.gitpushtogithup.png)

     - This sends the commits from main branch on my laptop to GitHub (Remote Repository)

## Part 2: Simulating Tom and Jerry's Work     




