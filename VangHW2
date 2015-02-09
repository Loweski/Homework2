// mult_func_constant project main.go
//Leng Vang Csci 130
package main

import (
	"fmt"
)

type Person struct {
	name     string
	position string
	course   string
}

const (
	answer = 42
)

func person_list(p Person) (string, string) {
	return "Hello " + p.name, ". " + "You are in " + p.course + "."
}
func main() {
	var person1 = Person{"Leng", "Student", "Csci 130"}
	fmt.Println(person_list(person1))
	fmt.Println("Remember, the answer is always ", answer, ".")
}
