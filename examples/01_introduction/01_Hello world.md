# Hello world

<div class="language-kotlin" theme="idea" data-min-compiler-version="1.3">

```kotlin
package org.kotlinlang.play         // 1

fun main() {                        // 2
    println("Salam, Dünya!")        // 3
}
```

</div>

1. Kotlin-də kodlar adətən package-lərdə (paketlərdə) təyin edilirlər. Əgər hər hansı biri təyin edilməzlərsə, susmaya görə package istifadə ediləcəkdir.
2. The main entry point to a Kotlin application is a function called *main* and since Kotlin 1.3 it can be a function without any parameters. 
3. `println` writes to standard output and is implicitly imported;
also, note that semicolons are optional.

Kotlinin versiyası 1.3-dən köhnə olduqda `main` funksiyası parametrlə təyin edilməlidir:
    
<div class="language-kotlin" theme="idea">

```kotlin
fun main(args: Array<String>) {
    println("Hello, World!")
}
```

</div>
