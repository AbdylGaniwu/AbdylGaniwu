
```
class Abdul_Ganiwu:
    def __init__(self):
        self.name = "Abdul Ganiwu"
        self.profession = "Pharmacy Technician"
        self.title = "ML/AI Engineer Enthusiast"
        self.contact = "abdyl.ganiwu@gmail.com"
        self.linkedin = "https://www.linkedin.com/in/abdul-ganiwu/"
        self.location = "Accra, Ghana"
        self.learning = "Data Science"
        self.collaboration_interest = "Looking to collaborate on exciting projects and learn"
        self.skills = ['Python', 'HTML', 'CSS', 'JavaScript', 'Microsoft SQL Server']

    def display_profile(self):
        profile = (
            f"Hi 👋 I'm {self.name}"
            f"Profession: {self.profession}"
            f"Title: {self.title}"
            f"Contact: {self.contact}"
            f"LinkedIn: {self.linkedin}"
            f"Location: {self.location}"
            f"Currently Learning: {self.learning}"
            f"Collaboration Interest: {self.collaboration_interest}"
            f"Skills: {', '.join(self.skills)}"
        )
        return profile

if __name__ == '__main__':
    print(AbdulGaniwu().display_profile())
