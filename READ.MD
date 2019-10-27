Code
```
package main

import "fmt"

func main() {
   fmt.Println("Hello, World!")
}
```
result
```
Hello, World!
```
In the most basic terms, A package is nothing but a directory inside your Go workspace containing one or more Go source files, or other Go packages. Every Go source file belongs to a package.

func main() creates a function and since go seperates codes by each line no semicolons are required

Code
```
package main

import "fmt"

func main() {
   var a, b, c = 3, 4, "foo"  
	
   fmt.Println(a)
   fmt.Println(b)
   fmt.Println(c)
   fmt.Printf("a is of type %T\n", a)
   fmt.Printf("b is of type %T\n", b)
   fmt.Printf("c is of type %T\n", c)
}
```

result
```
3
4
foo
int
int
string
```

you can add multiple variables in one line and give their value at the same time. 
You can Also Print the datatype using format '%T'

