#A03
Welcome to my README file. 

	It will guide you through basic concepts of Github.
		what is Git? --> 
			Git is distributed version control system for tracking changes in source code during software development. 
			It is designed for coordinating work among programmers. 
		What is Git Hub? 
			It is a subsidiary of microsoft, it supports development of git by providing a platform to developers to collaborate various projects. 
		
		What is Repository? 
			It is a home for all your projects. It's like a storage space that can store code files, text files, image files inside a repository.

		What is clone? 
			Clone is a command used to download a repository to a local computer. For example: git clone https://github.com/kp764/A03. 
		What is commit? 
			The commit commmand is used toi save your chnages to the local repository. It's like a snapchat of your code before you make changes.
		What is Push?
			Push is a command to upload code or commit to github.
		What is branch? 
			It helps to work with other collabators but makes new branch of commits.
		What is merge? 
				Merge is a command where you can make changes back to the master branch which is visible to all collaborators.
		What is merge conflict? 
			Merge conflicts happens when git gets confuse between two competing commits and needs your decision to decide which commit to keep.
		What is fetch? 
			The fetch command is used to downloaad the whole repository to see what everyone has commited.
		What is remote?
			A remote is a junction where team members can exchnage codes from remote repository.
			
		so how do we setup git?
			->we can do this several ways. If you want to use the desktop app then you can downloaad the exe file from https://desktop.github.com/
			->After installing the desktop app we can login to the app with our git hub account and manage repositorys, invite people,push updated commits and most of the stuff that can be done on website
			-> it is best idea to download and install git into the computer so that it can be accessed via command line. In linux and macOS the git command is alredy installed
					but in windows we need to install git from https://git-scm.com/download/win
			-> After installing git in windows the steps for all the operating systems is same.
			-> Make a folder on the hardisk and cd into it via terminal
				-> clone a repo in the folder by using clone command discussed above.
				-> next do $git init to initalize the git repository
				-> next do git add to add all the files in the repository
				-> now it is time to commit, type in the $git commit -m "message" to commit the file
				-> now add a remote to your directory so you can push changes anytime. to do that type $git remote add origin remote repository URL 
				-> now to push the changes do $git push -u origin master, this will push the new file to the repo
				
			we can check the status of the commit by typing $git status.
			
		after following all the steps you are ready to push and pull code from the repo as you please.
			
