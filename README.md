```kotlin
class Developer(val name: String, val languages: List<String>, val favorite: String, val github: String)

fun main() {
    val introduction = Developer(
        name = "Elaina",
        languages = listOf("Kotlin", "JavaScript", "Rust", "Java", "Vue.js", "C++"),
        favorite = "Kotlin",
        github = "@Shiiyuko"
    )

    println("Hello, my name is ${introduction.name}.")
    println("I am skilled in the following languages: ${introduction.languages.joinToString(", ")}.")
    println("My favorite language is ${introduction.favorite}.")
    println("You can find me on GitHub: ${introduction.github}.")
}

```

![Shiiyuko's GitHub stats](https://github-readme-stats.vercel.app/api?username=Shiiyuko&show_icons=true&theme=radical)

![Shiiyuko's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shiiyuko&layout=compact&theme=transparent)
