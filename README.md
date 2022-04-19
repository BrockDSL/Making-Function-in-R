![Tool Logo](Function-R.jpg)


# Making Functions in R
In this workshop you will get begin developing in R to the point that you can start crafting the tools that you need for the projects that are important to you. This workshop will cover:
 - If statements and conditionals
 - Three different kinds of Loops
 - And creating your own functions

----
## Setup Instructions
In preparation for this workshop, you will need to have an R Studio Cloud account and have a new project open.  Follow the steps below to get set up.

- (Skip this step if you already have an R Studio Cloud account) Begin by going to [https://rstudio.cloud/](https://rstudio.cloud/) and signing up for an account by clicking on the "Sign Up" text at the top right of the screen, then click the grey "Sign Up" button and fill in the form (or use the convenient Google or GitHub options if you have one of those accounts)
- Log in to R Studio Cloud
- You should arrive at your workspace.  From here click on the button that says, "New Project" and select "New R Studio Project"
- Once your project has finished building, open the "Source" window by clicking on the double box symbol in the top right corner of the "Console" window

![Source Button Location](image1.png)

 - Rename your project by clicking on the name at the top.  Name it whatever you like (eg. "Intro to R Workshop")

![Title Change](image2.png)

 - And thats it!  You are all set for the workshop

## Conditional Statement Symbols
| Symbol | Description |
|----|-------------|
| == | Is equal to |
| != | Is not equal to |
| < |	Is less than |
| <=	| Is less than or equal to |
| >	| Is greater than |
| >= |	Is greater than or equal to|


## Format of "if" statement
```R 

if (CONDITIONAL-STATEMENT) {
    CODE-TO-EXECUTE
    } else if (CONDITIONAL-STATEMENT) {
    CODE-TO-EXECUTE
    } else {
    CODE-TO-EXECUTE
    }
  
```

## Format of "for" loop
```R 
for (NEW-VARIABLE in VECTOR) {
    CODE-TO-EXECUTE
    }
```
## Format of  "while" loop
```R 
while (CONDITIONAL-STATEMENT) {
    CODE-TO-EXECUTE
}
```
## Format of "repeat" loop
```R 
repeat {
    CODE-TO-EXECUTE  (REMEMBER TO INCLUDE A break() TO STOP THE LOOP)
}
```
## Format for Function
```R 
FUNCTION-NAME <- function(ARGUMENT-VARIABLE-1, ARGUMENT-VARIABLE-2, …) {
return(OUTPUT-OF-FUNCTION)
}
```

## Workshop Tasks

**Task Set #1**  
  
  
**Task Set #2**  
 
  
**Task Set #3**  

  
**Task Set #4**  

  
**Task Set #5**  

  
**Task Set #6**  

## Follow Up Material
Add in names of books, links to websites, or any other reccomendations for follow up materials that could represent the "Next Step" in an attendees learning after the workshop.  helpful links like the Programming Historians or W3Schools are good examples.

 
 
 

  
**This workshop is brought to you by the Brock University Digital Scholarship Lab.  For a listing of our upcoming workshops go to [Experience BU](https://experiencebu.brocku.ca/organization/dsl) if you are a Brock affiliate or [Eventbrite page](https://www.eventbrite.ca/o/brock-university-digital-scholarship-lab-21661627350) for external attendees.**

