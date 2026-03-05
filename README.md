<!-- Animated Header -->
<div align="center" style="border: 3px solid #3B82F6; border-radius: 10px; padding: 10px;">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=190&section=header&text=Júlio%20Silva&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20|%20Software%20Engineer&descAlignY=55&descAlign=50" width="100%" />
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
        self.currently_learning = "Go"
        self.open_to_work       = False  # happily employed

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
  <a href="https://www.linkedin.com/in/julio-miguel-silva/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:julio.m.b.c.silva@gmail.com">
    <img src="https://img.shields.io/badge/Email-%23D14836.svg?&style=flat&logo=gmail&logoColor=white" />
  </a>
  <a href="https://jmbcs.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?&style=flat&logo=firefox&logoColor=white" />
  </a>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=jmbcs&style=flat-square&color=3B82F6" />
</div>
