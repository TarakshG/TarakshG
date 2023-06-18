"""
Name: Taraksh Garodia
Age: 16
Occupation: Tech Geek | Web Developer | Software Developer

Bio:
class Developer:
    def __init__(Taraksh, he/him, 16):
        self.name = Taraksh Garodia
        self.age = 16
        self.occupation = "Tech Geek | Web Developer | Software Developer"

    def get_bio(self):
        return f"Hello, fellow coders! I'm {self.name}, a {self.age}-year-old {self.occupation}."

class Skills:
    def __init__(self):
        self.languages = ["Python", "C++"]
        self.web_frameworks = ["MERN Stack"]
        self.interests = ["Netflix", "Coding"]

    def get_skills(self):
        return f"I'm currently honing my skills in {', '.join(self.languages)} and {', '.join(self.web_frameworks)}."
               f" Netflix and coding are my top interests!"

class Contact:
    def __init__(self, email):
        self.email = garodia06@gmail.com

    def get_contact_info(self):
        return f"Feel free to reach out to me at {self.email}."

me = Developer("Taraksh", 16)

my_skills = Skills()
contact_info = Contact("garodia06@gmail.com")

print(me.get_bio())
print(my_skills.get_skills())
print(contact_info.get_contact_info())
"""

