### Hi there 🖖🖖🖖 I´m Diego

```go
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}
                                                                  
func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "Hi i'm Diego, from Chile, i'm a Software Developer Student/Coder/Programmer/Nerd/Geek :sunglasses: :sunglasses: :sunglasses:",
		"- 🔭 I’m currently working on":      "Improve my coding skills",
		"- 🌱 I’m currently learning":        "Golang, Rust :crab: , JavaScript, Kotlin, Java, Dart, Flutter, Backend, BlockChain Technology, Android Development, Web Development",
		"- 👯 I’m looking to collaborate on": "Golang, Rust, Kotlin, Java, JavaScript",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Java, Kotlin, Software Development",
		"- 📫 How to reach me:":              "https://github.com/Dieg0Code",
	}
}
```
