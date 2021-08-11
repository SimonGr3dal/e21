# Git Cheatsheet (Kommandoer vi har brugt i undervisningen)

# Branching

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
	
