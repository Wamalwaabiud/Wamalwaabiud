<h1 align="center">Hi there, I'm Abiud Wamalwa 👋</h1>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="500px">
</p>

<h2 align="center">🧑‍💻 My Information</h2>

```go
package main

import "fmt"

type Person struct {
    name       string
    username   string
    age        int
    hobbies    []string
    job        string
}

func main() {
    me := Person{
        name:     "Abiud Wamalwa",
        username: "wamalwaabiud",
        age:      21,
        job:      "Software Developer & Data Scientist",
        hobbies:  []string{"coding", "RnB music", "problem-solving", "tech research"},
    }

    fmt.Println(me)
}
