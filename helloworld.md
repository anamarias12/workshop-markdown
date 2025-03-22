# Helloworld Programs

We list below Helloworld programs for different programming languages, i.e., programs that print "Hello, World!". The specified compiler or interpreter is required for each programming language.

## Summary Table

| Language   | Compiler/Interpreter |
|------------|----------------------|
| C          | GCC                  |
| C++        | G++                  |
| Dlang      | GDC                  |
| Go         | Golang               |
| Rust       | Rust (Crate)         |
| Java       | OpenJDK              |
| x86_64 Assembly | GCC / GAS       |
| ARM64 Assembly | GCC / GAS (AArch64) |
| Bash       | Bash                 |
| Python     | Python               |
| Ruby       | Ruby                 |
| PHP        | PHP                  |
| Perl       | Perl                 |
| Lua        | Lua                  |

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
