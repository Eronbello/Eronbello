# Eron Bello de Oliveira

## About Me

```golang
package main

import (
    "fmt"
)

type Bio map[string]string

func main() {
    for k, v := range GetBio() {
        fmt.Printf("%+v: %+v
", k, v)
    }
}

func GetBio() Bio {
    return Bio{
        "- ⚡ Quick bio:":                    "Front-end specialist with a strong focus on Vue.js and React, and extensive experience in full-stack development, leveraging Golang and Node.js on the back-end.",
        "- 🔭 I’m currently working on":      "Advanced micro front-end architectures at Wiley as a Senior Software Developer.",
        "- 🌱 I’m currently learning":        "Golang, Web 3 technologies, Blockchain, and enhancing my skills in Java and cloud-native technologies (AWS, K8s, Kafka).",
        "- 👯 I’m looking to collaborate on": "Cutting-edge front-end projects involving Vue.js, React, and full-stack applications with Golang or Node.js.",
        "- 🤔 I’m looking for help with":     "Anything that pushes the boundaries of front-end development, especially involving modern frameworks and performance optimization.",
        "- 💬 Ask me about":                  "Vue.js, React, front-end architecture, micro front-ends, Golang, Docker, and cloud infrastructure.",
    }
}
