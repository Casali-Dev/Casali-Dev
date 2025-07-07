[![Linkedin Badge](https://img.shields.io/badge/-Linkedin-6633cc?style=flat-square&logo=Linkedin&logoColor=white&color=black&link=https://www.linkedin.com/in/guilhermecasali/)](https://www.linkedin.com/in/guilhermecasali/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&color=black&link=mailto:guilhermecasali.dev@gmail.com)](mailto:guilhermecasali.dev@gmail.com)

<h1 align="center">Hi there 👋, I"m Guilherme Casali</h1>

```go
  package me

  import "fmt"

  type Dev struct {
    name string
    age int
    city string
    stack []string
  }

  func NextProject(choice int) {
    me := Dev{
      name: "Guilherme Lucca Casali",
      age: 27,
      city: "Porto Alegre - RS",
      stack: []string{"go", "next", "react", "node", "rust"},
    }
  
    fmt.Printf("Let's build a new project with %s!", me.stack[choice % len(me.stack)]);
  }
```
