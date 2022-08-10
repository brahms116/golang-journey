# First Golang Program

Here we are going to write our first golang program.

Create a file named `main.go` in the root directory and inside, type...

```golang
// main.go
package main

import "fmt"

func main() {
	fmt.Println("Hello world")
}
```

Now lets go through the above program line by line. There is actually quite a
little bit to unpack here.

**Package main**

Our first line `package main` tells the computer (it's actually the go
compiler, don't worry about the technicality here) that this file belongs to a
"package" called "main". Well what is a _package_? A program's computer code is
usually split into different groups or sections. We can think of these as
separate lego bricks which are combined to make a lego set, in our case, a
program.
