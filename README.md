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
<div align="center">

![Left](https://skillicons.dev/icons?i=go,nodejs,python,java,js,react,nextjs,express,rabbitmq&theme=dark&perline=3)&nbsp;&nbsp;&nbsp;![Stats](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=ayoszdeep&layout=compact&theme=tokyonight&hide_border=true&title_color=58A6FF&text_color=c9d1d9&bg_color=0d1117&card_width=340&langs_count=8)&nbsp;&nbsp;&nbsp;![Right](https://skillicons.dev/icons?i=mysql,docker,git,ts,linux,bash,redis,tailwind,html&theme=dark&perline=3)

</div>


<!-- <div align="center">
<img
  src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=ayoszdeep&layout=compact&theme=tokyonight&hide_border=true&title_color=58A6FF&text_color=c9d1d9&bg_color=0d1117&langs_count=10&card_width=680&custom_title=Languages&title_size=18&text_size=2"
  width="100%"
  alt="Top Languages"
/>
</div> -->
