# Eron Bello de Oliveira

## About Me

```rust
use std::collections::HashMap;

fn main() {
    let bio = get_bio();
    for (key, value) in bio {
        println!("{} {}", key, value);
    }
}

fn get_bio() -> HashMap<&'static str, &'static str> {
    let mut bio = HashMap::new();
    bio.insert("⚡ Quick bio:", "Seasoned Rust enthusiast forging memory-safe, high-performance applications across cloud-native landscapes.");
    bio.insert("🔭 Currently working on:", "Building robust backend microservices leveraging Rust’s fearless concurrency model.");
    bio.insert("🌱 Currently learning:", "Advanced async/await patterns, Tokio’s internals, and zero-cost abstractions that push performance boundaries.");
    bio.insert("👯 Looking to collaborate on:", "Cutting-edge Rust projects—whether it’s systems programming, WebAssembly experiments, or next-gen backend frameworks.");
    bio.insert("🤔 Seeking help with:", "Exploring new crates, harnessing unsafe optimizations responsibly, and unraveling dark corners of the Rust compiler.");
    bio.insert("💬 Ask me about:", "Ownership, lifetimes, macros, high-throughput async systems, and how to craft unstoppable Rust solutions.");
    bio
}

