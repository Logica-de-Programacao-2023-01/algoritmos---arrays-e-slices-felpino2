package main

import "fmt"

func main() {
	Conjunto := []int{1, 2, 3, 4, 5}
	var n1 int
	fmt.Println("Qual número você quer ver se está na lista? ")
	fmt.Scan(&n1)

	pertence := false
	for i := 0; i < len(Conjunto); i++ {
		{
			if Conjunto[i] == n1 {
				pertence = true
			}
		}
	}
	if pertence {
		fmt.Println("Este número já está no conjunto. ")
	} else {
		fmt.Println("O conjunto agora é ", append(Conjunto, n1))
	}
}
