### Hi there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class Security_engineer:

    def __init__(self):
        self.name = "Fabien Guihard"
        self.goals = "Pushing technical boundaries and contributing to open-source along the way."
        self.degree1 = "Double Master's degree - Cybersecurity"
        self.degree2 = "Bachelor's degree - Computer Science"
        self.universities = [
            ("University of Turku", "Finland"),
            ("University of Rennes", "France")
        ]
        self.language_spoken = ["EN", "FR"]
        self.skills = ["Linux hardening", "Embedded Linux development", "Yocto", "Post-Quantum Crypto"]

    def say_hi(self):
        print("Thanks for dropping by!")

me = Security_engineer()
me.say_hi()
``` 
