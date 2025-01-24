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
        fmt.Printf("%+v: %+v\n", k, v)
    }
}

func GetBio() Bio {
    return Bio{
        "- ⚡ Quick bio:":                    "Senior developer with a strong focus on building scalable, cloud-native applications and distributed systems.",
        "- 🔭 I’m currently working on":      "Designing and implementing high-performance APIs and microservices at Wellhub as a Senior Software Developer.",
        "- 🌱 I’m currently learning":        "Advanced Golang patterns, Web 3 technologies, Blockchain, and enhancing expertise in distributed systems and observability tools.",
        "- 👯 I’m looking to collaborate on": "High-impact back-end projects leveraging Golang, cloud-native solutions, and distributed architectures.",
        "- 🤔 I’m looking for help with":     "Exploring the latest advancements in Go, Kubernetes, and event-driven architectures using Kafka or RabbitMQ.",
        "- 💬 Ask me about":                  "Front end, React, Vue, Golang, microservices architecture, RESTful APIs, gRPC, Docker, Kubernetes, and scalable front-end solutions.",
    }
}
