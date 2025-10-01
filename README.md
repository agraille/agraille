<h1 align="center">Hi 👋,</h1>

```c++
#include <iostream>
#include <string>

class Student {
private:
    std::string name;
    std::string alias;
    std::string school;
    int completed_circles;
    int total_circles;

public:
    Student() : name("Anthony Graille"), alias("Lyricall"), school("42 Lyon"), completed_circles(6), total_circles(7) {}

    void introduce() const {
        std::cout << "Hi ! I'm " << name << ", alias " << alias << ".\n";
        std::cout << "Actually student at " << school << ".\n";
        std::cout << "Progress in the 42 common core: [";
        for (int i = 0; i < total_circles; i++) {
            std::cout << (i < completed_circles ? "🟢" : "⚪");
        }
        std::cout << "] " << completed_circles << "/" << total_circles << " circles completed!\n";
        std::cout << "Thank you for visiting my profile, I hope you find my work interesting !\n";
    }
};

int main() {
    Student me;
    me.introduce();
    return 0;
}
```
## 🔧 Technologies & Tools

<div align="left">

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=agraille&layout=compact)

# Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthony-graille-594385329/)
[![CodinGame](https://img.shields.io/badge/CodinGame-FFCE00?style=flat&logo=codinGame&logoColor=black)](https://www.codingame.com/profile/a6f595459899d5b746db8ee9dcd58f261407726)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:lachariotte30@gmail.com)
