AyoszDeep/README.md
```go
package main

import "fmt"

type Developer struct {
	Name           string
	Role           string
	Languages      []string
	CurrentlyDoing string
	FunFact        string
}

func (d *Developer) SayHi() {
	fmt.Println("Hey there 👋 Thanks for checking out my GitHub profile!")
	fmt.Println("I love building scalable backend systems, AI-powered applications, and solving real-world problems.")
}

func main() {
	me := Developer{
		Name:           "Ayoszdeep Mishra",
		Role:           "Backend & AI/ML Engineer",
		Languages:      []string{"Go", "JavaScript", "Java", "Python", "SQL"},
		CurrentlyDoing: "Building RAG pipelines, scalable REST APIs, and distributed systems",
		FunFact:        "Solved 350+ DSA problems and obsessed with system design 🚀",
	}

	me.SayHi()
}
```
