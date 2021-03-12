# Porcupine

Security oriented unit/functional testing library

![Porcupine Logo](./docs/img/porcupine.png)

## Context

Usually software are security-tested after release to detect potential injections and misbehavior. It means most of injections issues are supposed to be discovered at staging or even production level. 

## Shifting left

**Porcupine** follows the **shift-left** paradigm to help developers to detect security problems early in the development process. 

It aims at providing potential injection flaws at unit and functional testing level, and help developers test their code and its robustness while developing.

The library itself works a lot like **Faker** and other fake data providers. Through a factory you can request for different example of injection code and use it to test the output of your code.

## Examples

```
require porcupine
```