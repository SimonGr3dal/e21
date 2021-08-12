# Git Cheatsheet (Kommandoer vi har brugt i undervisningen)

## Branching

### Ny Branch
Lav en ny branch med et givent navn og skift til denne branch i samme hug.    

```` 
git checkout -b <navn> 
````
Denne metode vil tage ændringer fra det sidste commit i feks. "main" med over i den nye branch, og ikke have dem med i "main"

En alternativ metode er:    

````
git branch <navn>
git checkout <navn>
````

Denne metode vil __ikke__ tage ændringer fra det sidste commit i feks. "main" med over i den nye branch, og derfor have dem med i "main".
	
## Slette en branch
### Local branch

````
git branch -d <navn>

````

### Remote branch (github)
````
git push --delete origin <navn>

````

## Clone a branch

````
git clone <repo>
git branch 
*main
git branch -a
<all remotes>
git checkout -b origin/remote_branch

````




## TODOs

* git restore (discard changes from last commit)
* Fetch & pull
* git switch -c <new-branch-name>

* 
