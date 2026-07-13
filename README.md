# Hello World

## Fait

Nom        | Extension | Compilation + Execution
-----------|-----------|------------------------
Python     | `.py`     | `python monProgramme.py`
C          | `.c`      | `gcc monProgramme.c` + `./a.out`
C++        | `.cpp`    | `g++ monProgramme.cpp` + `./a.out`
C#         | `.cs`     | `dotnet new console -n TestCS` + `cd TestCS` + `dotnet run`
JS         | `.js`     | `node monProgramme.js`
Java       | `.java`   | `java monProgramme.java`
Go         | `.go`     | `go run monProgramme.go`
Rust       | `.rs`     | `rustc monProgramme.rs` + `./monProgramme`
Ruby       | `.rb`     | `ruby monProgramme.rb`
PHP        | `.php`    | `php monProgramme.php`
Bash       | `.sh`     | `bash monProgramme.sh`
Perl       | `.pl`     | `perl monProgramme.pl`
Lua        | `.lua`    | `lua monProgramme.lua`
TypeScript | `.ts`     | `node monProgramme.ts` 
Crystal    | `.cr`     | `crystal run monProgramme.cr` **OU** `crystal build monProgramme.cr` + `./monProgramme`


## A faire

Nom        | Extension | Compilation + Execution
-----------|-----------|------------------------
R          | `.r`      |
Crystal    | `.cr`     |
Dart       | `.dart`   |
Kotlin     | `.kt`     |

- **Crystal** :
  - Exécuter directement :
  ```bash
  crystal run monProgramme.cr
  ```
  > Ici Crystal compile automatiquement puis lance le programme.

  - Compiler + Exécuter :
  ```bash
  crystal build monProgramme.cr  # Compilation (ça génère un exécutable nommé : monProgramme)
  ./monProgramme                 # Exécution
  ```
  
