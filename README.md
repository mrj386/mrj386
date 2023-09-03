# Updating...

[anmation](https://gist.github.com/mrj386/b1968364db5067b3974757d479aa5d59)

``` Python
class AIEngineer:

    def __init__(self, name, role, skills):
        self.name = name
        self.role = role
        self.skills = skills

        self.social = {
            "Email" : "merajbokharaei.0@gmail.com"
            "Telegram" : "@mrj386_b"
        }
        
    def introduce(self):
        print(f"Hello, I am {self.name}, a {self.role}.")
        print("My skills include:")
        for skill in self.skills:
            print(f"- {skill}")


my_name = "Meraj Bokaraei"
my_role = "AI Engineer"
my_skills = ["Machine Learning", "Deep Learning", "Python", "Object-Oriented Programming"]


me = AIEngineer(my_name, my_role, my_skills)
me.introduce()
```

<!---
mrj386/mrj386 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
