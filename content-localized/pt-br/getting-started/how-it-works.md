---
title: "Olá Mundo: Como Funciona"
section: "Primeiros Passos"
menu:
  toc:
    parent: "getting-started"
    weight: 15
toc: true
---
Vamos olhar nosso `helloworld`:

```pony
actor Main
  new create(env: Env) =>
    env.out.print("Hello, world!")
```

Lorem ipsum dolor...