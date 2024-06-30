# Software Foundations

https://softwarefoundations.cis.upenn.edu/

## Setup

### Setup VSCoq

```bash
opam pin add coq 8.18.0
opam install vscoq-language-server.2.1.2
```

### Setup Makefile

```bash
coq_makefile -f _CoqProject **/*.v -o Makefile
```
