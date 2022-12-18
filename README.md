```python
#!/usr/bin/python

class SoftwareDeveloper:

    def __init__(self):
        self.name = "Remi S"
        self.role = "Software Developer"
        self.language_spoken = ["jp_JP", "en_US"]
        self.technologies = ["TypeScript", "C#", "Java", "Go", "C++", "Rust",
                             "Python", "express", "React", "OpenCV", "Keras"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting!")

    def say_other(self):
        print("I'm a hobbyist software developer that loves image processing and emojis! I also have a passion for NLP and CNNs! :)")


me = SoftwareDeveloper()
me.say_hi()
me.say_other()
```
