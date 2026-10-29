# LM1 Reading Assignment

## Reading Completed

Chapter 10 - Extending the Shell

## Key Takeaways

1. Pipeline binding first tries ByValue and then ByPropertyName
2. Expandproperty can allow you to see values inside property
3. Select-Object allows you to rename

## Function Practice

### Get-StudentName

Document your results here.

CODE:
function Get-StudentName {
    "Isaac Anderson"

}

When you type Get-StudentName, my full name will appear

### Get-CourseInfo

Document your results here.

CODE:
function Get-CourseInfo {
    $CourseName = "PowerShell Intermediate"

    $CourseName
}

Entering Get-CourseInfo will tell you the course

### Get-SystemInfo

Document your results here.

CODE:
function Get-SystemInfo {

    "Computer Name: $env:COMPUTERNAME"
    "Current Date: $(Get-Date)"
}

This one was a bit of a struggle, it uses other variables in play to output the information needed. It is getting the info from the computer. So now when you type in Get-SystemInfo, it will tell you your computer name and tell you the current date.

## Reflection

The most useful thing I learned from this reading was: Pipelines allows you to combine commands, which is great for creating functions. It's efficient 

The question I still have is: What other examples can do you with pipelines in scripts?
Commit the file to GitHub. 
