### Hi there 🖖🖖🖖 I´m Diego

```rust
use std::collections::HashMap;

fn main() {
    for (key, value) in &bio() {
        println!("{}{}", key, value);
    }
}

fn bio() -> HashMap<&'static str, &'static str> {
    let mut bio: HashMap<&str, &str> = HashMap::new();

    bio.insert(
        "- ⚡ Quick bio: ",
        "Hi i'm Diego, from Chile, i'm a Software Developer/Coder/Techy/Nerd/Student 😎",
    );
    bio.insert(
        "- 🔭 I’m currently working on: ",
        "Improving my Coding Skills 💻💻",
    );
    bio.insert(
        "- 📚 I’m currently Learning: ", 
        "Rust, Kotlin, Java 🧠🧠");
    bio.insert(
        "- 👯 I’m looking to collaborate on: ",
        "Rust, Kotlin, Java 😉😉",
    );
    bio.insert(
        "- 🤔 I’m looking for help with: ",
        "Anything related to what I am currently learning 😅",
    );
    bio.insert(
        "- 💬 Ask me about: ", 
        "Java, Kotlin, Rust, Android 👍👍");
    bio.insert(
        "- 📝 Contact me at: ",
        "twitter.com/Diegoobando0, linkedin.com/in/diego-obando-157809191 🤙🤙",
    );
    bio
}
```
## :trophy: My GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dieg0Code&theme=vue-dark)![GitHub stats](https://github-readme-stats.vercel.app/api?username=Dieg0Code&show_icons=true&theme=vue-dark)



