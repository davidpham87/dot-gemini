# dot-gemini
My .gemini config

## Why?

It acts as my place to keep my infrastructure for maintaining my MCP and gemini
configs.

## Constraints

- We aim to use clojure, either with clojure itself for the bindings to java, or
  with babashka for the speed and the ease of use.
- Emacs will be the IDE.
- gemini-cli as the main coding assistant tool.

We could abastract and relax the dependency, and we will aim to do so when
possible, but the goal is to solve my own constraints.

## Philosophy

We aim to use the least infra possible. The goal is to have a portable infra
from linux machine to the other with minimal steps.

## Extensions

Sub repos might be more helpful for repos though to install gemini extensions.

## Notes

Idea to explore:
    - clojure-mcp
    - mcp-clj

