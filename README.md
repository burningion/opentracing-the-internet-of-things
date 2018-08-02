# OpenTracing the Internet of Things

Tracing Experiments for the Internet of Things.

## What is this?

This will be an example repository showing a project we'll debug using Distributed Tracing. It's meant to showcase an example IoT project in Python with containers, while also showing how distributed tracing can be used to reason about / improve / diagnose distributed systems.

## How do I run it?

For now, the planned architecture will be a `docker-compose` that runs on a server, where the customers interact with. This server will then contact our edge nodes running Linux (either a Raspberry Pi w/ webcam or NVIDIA TX1/TX2), and get either webcam information or stats on things detected.

Through distributed tracing, we should be able to diagnose problems at both the edge device code, and the central web code. For now, this is just a placeholder.


