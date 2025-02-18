---
title: 'How to Implement Caching with Fastify'
sidebarTitle: 'Fastify'
parent: 'Caching'
---
# How to Implement Caching with Fastify

## What is Fastify?
Fastify is a web framework that provides a powerful plugin-based developer experience (inspired by Hapi and Express) with minimal overhead and is one of the fastest frameworks available, serving up to 30k requests per second. It is fully extensible via hooks, plugins, and decorators. Being schema-based, Fastify compiles schemas very efficiently. A TypeScript type declaration file is also maintained to support the growing TypeScript community.

## What is a Cache?
A cache is a short-term, high-speed data storage layer that stores a subset of data, enabling it to be retrieved faster than accessing it from its primary storage location. Caching allows you to reuse previously retrieved data efficiently.

## Caching Support in Keyv
Caching will work in memory by default. However, users can also install a Keyv storage adapter that is initialized with a connection string or any other storage that implements the Map API.

### Example - Add Cache Support Using Fastify
