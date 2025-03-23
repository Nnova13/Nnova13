<h1 align="center">
  <b> 👋 Hi, I'm Nnova!</b>
</h1>

Input:
```python
class Profile():
    
    def __init__(self):
        self.name = "Nnova"
        self.username = "Nnova13"
        self.age = 18
        self.mail = "nnova13@gmail.com"
        self.bio = "Developer Python | I like to code | Learning new technologies"
        self.skills = ["Python", "HTML", "CSS", "JavaScript"]
        self.projects = [
            {"name": "revers-art", "link": "https://github.com/Nnova13/2025_1093_revers-art"}
        ]
    
    def __str__(self):
        projects_str = "\n".join([f"  - [{project['name']}]({project['link']})" for project in self.projects])

        return f"""
👋 Hello, I'm {self.name}!
🔧 Bio: {self.bio}
🎂 Age: {self.age}
✉️ Email: {self.mail}

🛠 Skills:
  - {', '.join(self.skills)}

📂 Projects:
{projects_str}
        """

if __name__ == '__main__':
    me = Profile()
    print(me)
```
Output:
```bash
👋 Hello, I'm Nnova!
🔧 Bio: Developer Python | I like to code | Learning new technologies
🎂 Age: 18
✉️ Email: nnova13@gmail.com

🛠️ Skills:
  - Python, HTML, CSS, JavaScript

📂 Projects:
  - [revers-art](https://github.com/Nnova13/2025_1093_revers-art)
```
### GitHub Stats:

![Github Stats](https://github-readme-stats.vercel.app/api?username=Nnova13&show_icons=true&count_private=true&hide_title=true&hide=prs&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Nnova13&layout=compact&theme=radical)
