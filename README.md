```py
from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "Fosnos"
        self.age = "15"
        self.location = "Pluto"
        self.work = "Developer"
        self.system = "Windows 10, x64"

    def skills(self):
        self.languages = {
            "main": ["Python", "Java", "Node.js", "C#", "HTML/CSS/JS"],
            "learning": ["golang", "C++"]
        }

        self.works = ['Token Generator', 'hCaptcha Bypass', 'Chat Botter', 'Shill Tool', 'Token Manager', 'etc...']
    
    def social_media(self):
        self.discord = "Fosnos#5529"
        self.telegram = "tcpskid"
        self.instagram = "sammbtw"
        self.onlyfans = None


if __name__ == "__main__":
    readme = GithubReadme.create(Fosnos)```
