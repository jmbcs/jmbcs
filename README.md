<!-- Animated Header -->
<div align="center" style="border: 3px solid #3B82F6; border-radius: 10px; padding: 10px;">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=190&section=header&text=Júlio%20Silva&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20|%20Software%20Engineer&descAlignY=55&descAlign=50" width="100%" />
</div>
<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julio-miguel-silva/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:julio.m.b.c.silva@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF7139?style=flat&logo=firefox-browser&logoColor=white)](https://jmbcs.github.io/portfolio/)
[![Profile Views](https://komarev.com/ghpvc/?username=jmbcs&style=flat&color=3B82F6&label=Views)](https://github.com/jmbcs)
</div>

```python3
class BackendDeveloper:

    def __init__(self):
        self.name               = "Júlio Silva"
        self.role               = "Backend Developer"
        self.location           = "Portugal 🇵🇹"
        self.company            = "GuestReady / RentalReady"

        self.languages          = ["Python", "Go", "JavaScript", "Bash"]
        self.frameworks         = ["Django", "FastAPI", "Django REST Framework"]
        self.databases          = ["PostgreSQL", "Redis"]
        self.tools              = ["Docker", "Git", "Linux", "Celery", "RabbitMQ"]
        self.monitoring         = ["Sentry", "Datadog", "Grafana", "VictoriaMetrics"]

        self.interests          = ["Clean architecture", "API design",
                                   "Performance optimization", "Distributed systems"]
        self.currently_learning = "A.I workflow"

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

    def get_daily_routine(self) -> list[str]:
        return [
            "coffee.brew()",
            "git pull --rebase",
            "write_clean_code(tests_first=True)",
            "review_pull_requests()",
            "optimize_queries(n=float('inf'))",
            "git commit -m "'done with extra caffeine'",
            "git push",
            "coffee.brew()  # again",
        ]

    def contact(self) -> dict:
        return {
            "email":     "julio.m.b.c.silva@gmail.com",
            "linkedin":  "linkedin.com/in/julio-miguel-silva/",
            "portfolio": "jmbcs.github.io/portfolio/",
        }

    def __repr__(self) -> str:
        return f"<BackendDeveloper name={self.name!r} role={self.role!r}>"

if __name__ == "__main__":
    me = BackendDeveloper()
    me.say_hi()
    print(me)
```



<!-- Footer Section -->


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=120&section=footer" width="100%" />
  <p><i>"Code is like humor. When you have to explain it, it's bad." – Cory House</i></p>
</div>
