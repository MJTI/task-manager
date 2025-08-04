# Project 1.3 :

	2.b task :
		- git add tasks.txt
		- git commit -m "adding tasks file"

	3.b task :
		- git add .
		- git commit -m "commit message"
	
	3.c :
		- git switch main
		- git checkout -b feature/remove-tasks

	4.a :
		- git switch main
		- git merge main feature/add-tasks
		- git merge main feature/remove-tasks
	4.b :
		- vim tasks.txt "to resolve the conflict manually"
		- git add . 
		- git commit -m "conflict resolved"

	5.a : 
		- git checkout -b feature/update-tasks
	
	5.c : 
		- git switch main
		- git rebase feature/update-tasks

	7.b :
		- git log --oneline
		- git revert "commit SHA"

	8.b : 
		- git push -u origin main



