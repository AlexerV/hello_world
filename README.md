<h1 align="center">Hello World</h1>

<!--
## Fait

Nom        | Extension | Compilation + Execution
-----------|-----------|------------------------
~~Python~~ | `.py`     | `python monProgramme.py`
~~C~~      | `.c`      | `gcc monProgramme.c` + `./a.out`
~~C++~~    | `.cpp`    | `g++ monProgramme.cpp` + `./a.out`
~~C#~~     | `.cs`     | `dotnet new console -n TestCS` + `cd TestCS` + `dotnet run`
~~JS~~     | `.js`     | `node monProgramme.js`
~~Java~~   | `.java`   | `java monProgramme.java`
~~Go~~     | `.go`     | `go run monProgramme.go`
~~Rust~~   | `.rs`     | `rustc monProgramme.rs` + `./monProgramme`
~~Ruby~~   | `.rb`     | `ruby monProgramme.rb`
~~PHP~~    | `.php`    | `php monProgramme.php`
~~Bash~~   | `.sh`     | `bash monProgramme.sh`
~~Perl~~   | `.pl`     | `perl monProgramme.pl`
~~Lua~~    | `.lua`    | `lua monProgramme.lua`
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

-->

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
<summary>C#</summary>

Extension : `.cs`  
Compilation :
```bash
dotnet new console -n TestCS
cd TestCS
```
Exécution :
```bash
dotnet run
```

</details>

<details>
<summary>JavaScript</summary>

Extension : `.js`  
Exécution :
```bash
node monProgramme.js
```

</details>

<details>
<summary>Java</summary>

Extension : `.java`  
Exécution :
```bash
java monProgramme.java
```

</details>

<details>
<summary>Go</summary>

Extension : `.go`  
Exécution :
```bash
go run monProgramme.go
```

</details>

<details>
<summary>Rust</summary>

Extension : `.rs`  
Compilation :
```bash
rustc monProgramme.rs
```
Exécution :
```bash
./monProgramme
```

</details>

<details>
<summary>Ruby</summary>

Extension : `.rb`  
Exécution :
```bash
ruby monProgramme.rb
```

</details>

<details>
<summary>PHP</summary>

Extension : `.php`  
Exécution :
```bash
php monProgramme.php
```

</details>

<details>
<summary>Bash</summary>

Extension : `.sh`  
Exécution :
```bash
bash monProgramme.sh
```

</details>

<details>
<summary>Perl</summary>

Extension : `.pl`  
Exécution :
```bash
perl monProgramme.pl
```

</details>

<details>
<summary>Lua</summary>

Extension : `.lua`  
Exécution :
```bash
lua monProgramme.lua
```

</details>

<details>
<summary>TypeScript</summary>

Extension : `.ts`  
Exécution :
```bash
node monProgramme.ts
```

</details>

<details>
<summary>Crystal</summary>

Extension : `.cr`  
Compilation :
```bash
crystal build monProgramme.cr
```
Exécution :
```bash
./monProgramme
```
**OU**  
Exécution sans compilation :
```bash
crystal run monProgramme.cr
```
> Ici Crystal compile automatiquement puis lance le programme.

</details>


<details>
<summary>Kotlin</summary>

Extension : `.kt`  
Compilation :
```bash
kotlinc monProgramme.kt -include-runtime -d monProgramme.jar  # (L'option `-include-runtime` inclut la bibliothèque standard Kotlin dans le JAR.)
```
Exécution :
```bash
java -jar monProgramme.jar  # Exécution avec Java
```

Exécution sans créer de JAR :
```bash
kotlinc monProgramme.kt -d .  # Compilation
kotlin MonProgrammeKt  # Exécution
```
> `MonProgrammeKt` correspond au nom du fichier `monProgramme.kt`.

</details>


<details>
<summary>Dart</summary>

Extension : `.dart`  
Compilation :
```bash
dart compile exe monProgramme.dart -o monProgramme
```
Exécution :
```bash
./monProgramme
```
Exécution sans compilation :
```bash
dart run monProgramme.dart
# ou
dart monProgramme.dart
```
> Selon la version du SDK Dart installée, `dart run` est la commande recommandée.

Compiler en JavaScript
```bash
dart compile js monProgramme.dart -o monProgramme.js  # Compilation en JavaScript
node monProgramme.js  # Exécution
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
