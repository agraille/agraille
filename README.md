<h1 align="center">Hi 👋,</h1>

```c
#include <stdio.h>
#include <string.h>

struct Student {
    char name[42];
    char alias[42];
    char school[42];
    char completed_projects[9][42];
};

void initializeStudent(struct Student *student) {
    strcpy(student->name, "Anthony Graille");
    strcpy(student->alias, "Lyricall");
    strcpy(student->school, "42 Lyon");
    strcpy(student->completed_projects[0], "libft");
    strcpy(student->completed_projects[1], "ft_printf");
    strcpy(student->completed_projects[2], "born2beroot");
    strcpy(student->completed_projects[3], "get_next_line");
    strcpy(student->completed_projects[4], "push_swap");
    strcpy(student->completed_projects[5], "so_long");
    strcpy(student->completed_projects[6], "pipex");
    strcpy(student->completed_projects[7], "minishell");
    strcpy(student->completed_projects[8], "Philosophers");
}

void introduceStudent(const struct Student *student) {
    printf("Hi ! I'm %s, alias %s.\n", student->name, student->alias);
    printf("Actually student at %s.\n", student->school);
    printf("Here are some projects I have completed :\n");
    for (int i = 0; i < 8; i++) {
        printf("- %s\n", student->completed_projects[i]);
    }
    printf("Thank you for visiting my profile, I hope you find my work interesting !");
}

int main(void) {
    struct Student me;
    initializeStudent(&me);
    introduceStudent(&me);

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
