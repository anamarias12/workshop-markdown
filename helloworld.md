# Helloworld Programs

![Hello World](helloworld.png)

We list below Helloworld programs for different programming languages, i.e., programs that print "Hello, World!". The specified compiler or interpreter is required for each programming language.

The table below summarizes the programs:

## Summary Table

| Language         | Language (Spec) Site                                  | Section          | Build / Run Toolchain     | Debian / Ubuntu Packages         |
|-----------------|------------------------------------------------------|------------------|---------------------------|----------------------------------|
| C               | [The Standard - C](https://www.open-std.org/jtc1/sc22/wg14/) | [C](#c)         | GCC                       | build-essential                |
| C++             | [The Standard - C++](https://isocpp.org/)            | [C++](#c++)     | GCC / G++                  | build-essential, g++           |
| Dlang          | [D Programming Language: Home](https://dlang.org/)    | [Dlang](#dlang) | GCC / GDC                  | build-essential, gdc           |
| Go              | [The Go Programming Language](https://golang.org/)    | [Go](#go)       | Go                         | golang                          |
| Rust            | [Rust Programming Language](https://www.rust-lang.org/) | [Rust](#rust) | Rust (Crate)               | rustlang                        |
| Java            | [Java Programming Language](https://www.oracle.com/java/) | [Java](#java) | JDK                         | openjdk-17-jdk                  |
| x86_64 assembly | [x86 and amd64 instruction reference](https://www.felixcloutier.com/x86/) | [x86_64 Assembly](#x86_64-assembly) | GCC / GAS          | build-essential                |
| ARM64 assembly  | [Arm A64 Instruction Set Architecture](https://developer.arm.com/documentation/ddi0596/) | [ARM64 Assembly](#arm64-assembly) | GCC / GAS (AArch64) | build-essential                |
| Bash            | [Bash Reference Manual](https://www.gnu.org/software/bash/manual/) | [Bash](#bash) | Bash                       | bash                            |
| Python          | [Welcome to Python.org](https://www.python.org/)     | [Python](#python) | Python                   | python                          |
| Ruby            | [Ruby Programming Language](https://www.ruby-lang.org/en/) | [Ruby](#ruby) | Ruby                      | ruby                            |
| PHP             | [PHP: Hypertext Preprocessor](https://www.php.net/)   | [PHP](#php)     | PHP                         | php                             |
| Perl            | [The Perl Programming Language](https://www.perl.org/) | [Perl](#perl) | Perl                        | perl                            |
| Lua             | [The Programming Language Lua](https://www.lua.org/) | [Lua](#lua)     | Lua                         | lua                             |


## Code Samples

### C
```c
#include <stdio.h>

int main(void) {
    puts("Hello, World!");
    return 0;
}
```
**Build and Run:**
```sh
gcc -Wall -o helloworld helloworld.c
./helloworld
```

### C++
```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```
**Build and Run:**
```sh
g++ -Wall -o helloworld helloworld.cpp
./helloworld
```

### Dlang
```d
import std.stdio;

void main() {
    writeln("Hello, World!");
}
```
**Build and Run:**
```sh
gdc -Wall -o helloworld helloworld.d
./helloworld
```

### Go
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
**Run:**
```sh
go run helloworld.go
```

### Rust
```rust
fn main() {
    println!("Hello, World!");
}
```
**Build and Run:**
```sh
rustc hello.rs
./helloworld
```

### Java
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
**Build and Run:**
```sh
javac HelloWorld.java
java HelloWorld
```

### Bash
```sh
echo "Hello, World!"
```
**Run:**
```sh
bash helloworld.sh
```

### Python
```python
print("Hello, World!")
```
**Run:**
```sh
python helloworld.py
```

### Ruby
```ruby
puts "Hello, World!"
```
**Run:**
```sh
ruby helloworld.rb
```

### PHP
```php
<?php
echo "Hello, World!";
?>
```
**Run:**
```sh
php helloworld.php
```

### Perl
```perl
print("Hello, World!\n");
```
**Run:**
```sh
perl helloworld.pl
```

### Lua
```lua
print("Hello, World!")
```
**Run:**
```sh
lua helloworld.lua
