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
        "- ⚡ Quick bio:": "Seasoned developer forging cloud-native, scalable applications and distributed systems with unwavering precision.",
        "- 🔭 Currently working on:": "Architecting high-performance APIs and microservices at Wellhub as a Senior Software Developer, orchestrating robust back-end solutions.",
        "- 🌱 Currently learning:": "Advanced Go design patterns, blockchain fundamentals (Web3), and delving deeper into distributed systems, observability, and performance tuning.",
        "- 👯 Looking to collaborate on:": "Cutting-edge back-end projects leveraging Go, Kubernetes, microservices, and event-driven architectures built around Kafka or RabbitMQ.",
        "- 🤔 Seeking help with:": "Exploring the latest innovations in cloud orchestration, concurrency patterns, and real-time data processing—where performance meets reliability.",
        "- 💬 Ask me about:": "Everything from front-end frameworks (React, Vue) and Golang best practices to microservices architecture, RESTful APIs, gRPC, Docker, Kubernetes, and scalable front-end solutions.",
    }
}

