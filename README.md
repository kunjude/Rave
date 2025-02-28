<h1 align="center">Rave Language</h1>

Rave is a statically typed, compiled, procedural, general-purpose programming language.

## "Hello, world!" Example

```nasm
import <std/io>

void main {
    std::println("Hello, world!");
}
```

You can compile are examples using `rave directory/of/Rave/examples/necessary_example.rave -o preffered/directory/necessary_example`

## Dependencies

* `llvm-11` (including clang-11)
* dub and dmd(or ldc/gdc) compiler

## Building/Running

To install dependencies, you can try running `install.sh` (Ubuntu/Debian) or `install.ps1` (Windows).

If the installer does not work well on your system, you can try to install all the dependencies yourself.

After install write `dub build` in the Rave directory.

## Reference

The reference is in `reference` directory.

<a href="https://github.com/Ttimofeyka/Rave/blob/main/bindings.md">Bindings</a>

<a href="https://discord.gg/AfEtyArvsM">Discord</a>

<a href="https://www.ravelang.tk/">Web-site</a>

