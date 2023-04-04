package main

import "fmt"

func main() {
	var a string
	Conjunto := []string{"Alice", "Bernardo", "Carlos", "Felipe", "Luis", "Marcos", "João", "Caio"}
	fmt.Println("Sua lista é ", Conjunto, "que nome você quer remover? ")
	fmt.Scan(&a)
	for i := 0; i < len(Conjunto); i++ {
		if a == Conjunto[i] {
			fmt.Println(append(Conjunto[:i], Conjunto[i+1:]...))
		}
	}
}
