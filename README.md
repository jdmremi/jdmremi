```python
#!/usr/bin/python

class SoftwareDeveloper:

    def __init__(self):
        self.name = "Remi S"
        self.role = "Student, Software Developer"
        self.language_spoken = ["jp_JP", "en_US", "es_MX"]
        self.technologies = ["TypeScript", "C#", "Java", "Go", "C++", "Rust",
                             "Python", "express", "React", "OpenCV", "Keras", "pandas", "NumPy"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting!")

    def say_other(self):
        print("I'm a student and software developer with an interest in a lot of different things. I particularly enjoy working with data, image processing, music, AI/ML, and whatever interests me in that moment.")


me = SoftwareDeveloper()
me.say_hi()
me.say_other()
```
