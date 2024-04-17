### Hi there 🖖🖖🖖 I´m Diego

```rust
// Biography 📗

// This code is an updated biography about me and my interests in technology, based on recent achievements.

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
        "Hi there! 👋\n\nI'm Diego, a recent graduate with \n\
        a Technical Degree in Programming and Systems \n\
        Analysis from AIEP Institute. I'm passionate 🔥\n\
        about software development, particularly \n\
        backend technologies like Java and Spring Boot.\n\n\
        I believe programming is a powerful tool to \n\
        turn ideas into reality 💡, and I enjoy exploring \n\
        how we can use technology to solve real-world \n\
        problems efficiently and innovatively. 🚀\n"
    );

    bio.insert(
        "# 💻 My Interests :\n",
        "As a backend developer, I'm fascinated by \n\
        designing and building robust APIs 🌐, working \n\
        with databases 📂, and implementing clean \n\
        architectures 🏗️. I'm also interested in \n\
        cybersecurity 🔒, cloud computing ☁️, and exploring \n\
        the latest industry trends and best practices. 🆕\n"
    );

    bio.insert(
        "# 🚀 My Experience :\n",
        "I've had the opportunity to work as a Backend \n\
        Developer at WorkCapIT, where I gained \n\
        hands-on experience with Java 17, Spring Boot, \n\
        PostgreSQL, and Git version control. I also \n\
        completed an internship as a Software Engineer, \n\
        developing with Node.js, Express, and TypeScript.\n\n\
        You can find some of my personal projects 💻\n\
        showcased on this GitHub profile, where I \n\
        share coding exercises, experiments, and \n\
        ongoing learning. 📚\n"
    );

    bio.insert(
        "# 📜 Certifications & Skills :\n",
        "In addition to my technical degree, I've \n\
        completed several online courses and \n\
        certifications related to Java, Kotlin, \n\
        JavaScript, Android development, and \n\
        Object-Oriented Programming. My primary \n\
        technical skills include TypeScript, Java, \n\
        Spring Boot, and I'm always eager to learn more. 📈\n"
    );

    bio.insert(
        "# 📞 Contact Me :\n",
        "If you'd like to get in touch with me, you \n\
        can find me on LinkedIn at \n\
        https://www.linkedin.com/in/diego-obando/. \n\
        I'm open to new opportunities 💼, collaborations 🤝, \n\
        or just to connect and discuss technology. 🗣️\n\
        Let's explore what we can create together! 🚀\n"
    );

    bio
}
```
## 🏴‍☠️ My GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dieg0Code&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&layout=pie)![GitHub stats](https://github-readme-stats.vercel.app/api?username=Dieg0code&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true)



