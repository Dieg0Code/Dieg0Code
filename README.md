### Hi there 🖖🖖🖖 I´m Diego

```rust
// Biography
// This code is a brief biography about me and my interests in technology.
// Run this on https://play.rust-lang.org/

use std::collections::HashMap;

type Bio = HashMap<&'static str, &'static str>;

fn main() {
    for (k, v) in bio().iter() {
        println!("{}{}", k, v);
    }
}

fn bio() -> Bio {
    let mut bio: Bio = HashMap::new();

    bio.insert(
        "👋 About Me :\n",
        "Hi there! 👋
        I'm Diego, a programming student with a passion for mobile development 📱 and cybersecurity 💻. 
        I believe programming is a tool that enables us to turn our ideas 💡 into reality ✨ (and 💸), and I enjoy
        exploring how we can use technology to solve real-world problems 🤔."
    );

    bio.insert(
        "# 💻 My Interests :\n",
        "As a mobile developer 📱, I love creating intuitive and user-friendly
        apps that people can use on-the-go 💖. I'm also interested in cybersecurity and how we can protect
        our systems and data from malicious attacks 🔒."
    );

    bio.insert(
        "# 🚀 My Projects :\n",
        "This GitHub repository is a showcase of my work 🏴‍☠️, where I share
        projects I've been working on, ideas I'm exploring, and concepts I'm learning 📝.
        If you're looking for a programming student who's passionate, hardworking, and curious, then look no further 😎.
        Let's connect and explore the possibilities of what we can create together! 💻"
    );

    bio.insert(
        "# 📞 Contact Me :\n",
        "If you'd like to get in touch with me, you can find me
        on LinkedIn at https://www.linkedin.com/in/diego-obando/. I'm looking forward to hearing from you!"
    );

    bio
}
```
## :trophy: My GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dieg0Code&theme=vue-dark)![GitHub stats](https://github-readme-stats.vercel.app/api?username=Dieg0Code&show_icons=true&theme=vue-dark)



