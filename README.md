<h1 align="center">Hello World</h1>

## Fait

Nom        | Extension | Compilation + Execution
-----------|-----------|------------------------
~~Python~~ | `.py`     | `python monProgramme.py`
~~C~~      | `.c`      | `gcc monProgramme.c` + `./a.out`
~~C++~~    | `.cpp`    | `g++ monProgramme.cpp` + `./a.out`
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
Kotlin     | `.kt`     | `kotlinc monProgramme.kt -include-runtime -d monProgramme.jar` + `java -jar monProgramme.jar` **OU** `kotlinc monProgramme.kt -d .` + `kotlin MonProgrammeKt`
Dart       | `.dart`   | `dart compile exe monProgramme.dart -o monProgramme` + `./monProgramme` **OU** `dart run monProgramme.dart` **OU** `dart monProgramme.dart`


## A faire

Nom        | Extension
-----------|----------
R          | `.r`

---

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

---
  
- **Kotlin** :
  - Compilation + Exécution :
  ```bash
  kotlinc monProgramme.kt -include-runtime -d monProgramme.jar  # (L'option `-include-runtime` inclut la bibliothèque standard Kotlin dans le JAR.)
  java -jar monProgramme.jar  # Exécution avec Java
  ```

  - Exécuter sans créer de JAR
  ```bash
  kotlinc monProgramme.kt -d .  # Compiler
  kotlin MonProgrammeKt  # Exécuter
  ```
  > `MonProgrammeKt` correspond au nom du fichier `monProgramme.kt`.

---

- **Dart** :
  - Exécuter directement :
  ```bash
  dart run monProgramme.dart
  # ou
  dart monProgramme.dart
  ```
  > Selon la version du SDK Dart installée, `dart run` est la commande recommandée

  - Compiler en exécutable natif :
  ```bash
  dart compile exe monProgramme.dart -o monProgramme  # Compilation
  ./monProgramme  # Exécution
  ```

  - Compiler en JavaScript :
  ```bash
  dart compile js monProgramme.dart -o monProgramme.js  # Compilation en JavaScript
  node monProgramme.js  # Exécution
  ```

---

<details>
<summary>Python</summary>

Extension : `.py`  
Exécution :
```bash
python monProgramme.py
```

</details>

<details>
<summary>C</summary>

Extension : `.c`  
Compilation :
```bash
gcc monProgramme.c
```
Exécution :
```bash
./a.out
```

</details>

<details>
<summary>C++</summary>

Extension : `.cpp`  
Compilation :
```bash
g++ monProgramme.cpp
```
Exécution :
```bash
./a.out
```

</details>

<details>
<summary>Template</summary>

Extension : ``  
Compilation :
```bash

```
Exécution :
```bash

```

</details>
