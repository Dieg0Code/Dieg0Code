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
        "Hi there! 👋\n\nI'm Diego, a passionate 🔥 and skilled \n\
        software developer specializing in backend \n\
        technologies. With a recent technical degree 🎓\n\
        in Programming and Systems Analysis, I'm ready \n\
        to tackle challenging projects.\n\n\
        I believe programming is a powerful tool to bring \n\
        ideas to life 💡, and I strive to create efficient \n\
        and innovative solutions for real-world problems. 🌐\n"
    );

    bio.insert(
        "# 💻 My Expertise :\n",
        "As a backend developer, I excel in designing and \n\
        building robust APIs 🌐, working with databases 📂,\n\
        and implementing clean architectures 🏗️. I'm also \n\
        passionate about cybersecurity 🔒, cloud computing ☁️,\n\
        and staying up-to-date with industry trends. 🆕\n"
    );

    bio.insert(
        "# 🚀 Experience & Projects :\n",
        "I've gained hands-on experience working as a \n\
        Backend Developer, utilizing Java 17, Spring Boot,\n\
        PostgreSQL, and Git version control. Additionally,\n\
        I completed an internship as a Software Engineer, \n\
        developing with Node.js, Express, and TypeScript.\n\n\
        Check out my GitHub profile to explore personal \n\
        projects 💻 where I showcase coding exercises, \n\
        experiments, and continuous learning endeavors. 📚\n"
    );

    bio.insert(
        "# 📜 Skills & Certifications :\n",
        "In addition to my degree, I've completed several \n\
        online courses and certifications in Java, Kotlin,\n\
        JavaScript, Android development, and Object-Oriented\n\
        Programming. My core technical skills include \n\
        TypeScript, Java, Spring Boot, and a passion for \n\
        continuous learning and growth. 📈\n"
    );

    bio.insert(
        "# 📫 Let's Connect :\n",
        "I'm actively seeking new opportunities 💼 to \n\
        contribute my skills and experience. Feel free \n\
        to reach out on LinkedIn: \n\
        https://www.linkedin.com/in/diego-obando/\n\
        I'm open to collaborations 🤝, discussions about \n\
        technology 🗣️, and exploring what we can create \n\
        together. Let's build something amazing! 🚀\n"
    );

    bio
}
```
## 🏴‍☠️ My GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dieg0Code&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&layout=pie)![GitHub stats](https://github-readme-stats.vercel.app/api?username=Dieg0code&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true)



