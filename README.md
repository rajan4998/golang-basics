# golang-basics

Basic concepts : Variable names

1. Variable names are case-sensitive
    Eg : 
    a := 5
    A := 5
    These are 2 different variables in Golang
2. Go-programmers are suggested to use camelCase as variable naming convention, regardless of Data type
    Eg : totalSum := 0
         userName := "Rajan"
3. It's not recommended to use "_" (underscore) in variable names. Though there will be no no error that will be popped out, but IDE will show Green line underneath the variable.
4. Short variable names are suggested
    Eg : Instead of 
            userName := "Rajan"
            u := "Rajan"
        should be preferred
