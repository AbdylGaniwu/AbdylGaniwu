```
class Abdul_Ganiwu:
    def __init__(self):
        self.name = "Abdul Ganiwu"
        self.profession = "Pharmacy Technician"
        self.title = "ML/AI Engineer Enthusiast"
        self.contact = "abdyl.ganiwu@gmail.com"
        self.linkedin = "https:/www.linkedin.com/in/abdul-ganiwu/"
        self.location = "Accra, Ghana"
        self.learning = "Data Science"
        self.collaboration_interest = "Looking to collaborate on exciting projects and learn"
        self.skills = ['Python', 'HTML', 'CSS', 'JavaScript', 'Microsoft SQL Server']

    def display_profile(self):
        profile = (
            f"Hi 👋 I'm {self.name}\n"
            f"Profession: {self.profession}\n"
            f"Title: {self.title}\n"
            f"Contact: {self.contact}\n"
            f"LinkedIn: {self.linkedin}\n"
            f"Location: {self.location}\n"
            f"Currently Learning: {self.learning}\n"
            f"Collaboration Interest: {self.collaboration_interest}\n"
            f"Skills: {', '.join(self.skills)}\n"
        )
        return profile

if __name__ == '__main__':
    print(Abdul_Ganiwu().display_profile())
