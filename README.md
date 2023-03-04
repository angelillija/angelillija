```py
class Profile:
    def __init__(self, username, name, location, telegram, discord, bio, website, skills, learning, interests, projects):
        self.username = username
        self.name = name
        self.location = location
        self.telegram = telegram
        self.discord = discord
        self.bio = bio
        self.website = website
        self.skills_list = skills
        self.learning_list = learning
        self.interests_list = interests
        self.projects_list = projects

    def about_me(self):
        print(f"👋 Hi there! My name is {self.name}. I am from {self.location}. {self.bio}")

    def contact_info(self):
        print(f"📫 You can reach me via Telegram ({self.telegram}) or Discord ({self.discord}). 💻 Visit my website: {self.website}.")

    def skills(self):
        print(f"🤹 My skills: {', '.join(self.skills_list)}.")

    def learning(self):
        print(f"📚 I'm currently learning: {', '.join(self.learning_list)}.")

    def interests(self):
        print(f"🌟 My interests: {', '.join(self.interests_list)}.")

    def projects(self):
        print(f"🚀 My projects: {', '.join(self.projects_list)}.")


aithedev = Profile(
    username="aithedev", 
    name="ai", 
    location="USA", 
    telegram="t.me/aithedev", 
    discord="ai#4444", 
    bio="Developer & Reverse Engineer", 
    website="https://aithe.dev", 
    skills=["Python", "HTML", "CSS", "Reverse Engineering"], 
    learning=["JavaScript"],
    interests=["Reverse Engineering", "Machine learning", "Web development", "Malware"],
    projects=["TikTok Account Generator", "TikTok Mobile API", "X-Gorgon"]
)

aithedev.about_me()
aithedev.contact_info()
aithedev.projects()
aithedev.skills()
aithedev.interests()
aithedev.learning()
```
