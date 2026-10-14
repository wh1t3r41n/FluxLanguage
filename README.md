# Flux Language

> *Status* Developing from scratch on C 'n' llvm!
- Flux -> Procedural-oriantation, imperative, functional language with strict static typezation! Syntax -> C-asm-liked! Specifical language for first develop!

## Example

### Hello world

```c
join fluxlib : io;
join fluxlib : main;

section start {
  int main(char[] **args) -> main::function {
    io::print("hello world");
    return 0;
  }
  end_section start;
}
```
