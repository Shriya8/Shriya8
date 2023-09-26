```
class SoftwareDeveloper:
    def __init__(self):
        self.name = "Shriya Char"
        self.languages = ["Python", "Java", "C++", "Pascal"]
        self.tools = ["Git", "IDEA", "HTML/CSS/JavaScript"]
        self.interests = ["Research", "Software Development", "Cybersecurity", "AI"]
        self.hobbies = ["Piano", "Roller Skating", "Skiing", "Reading"] 

    def greet(self):
        print("Hi there! 👋 I'm Shriya Char, a Software Developer.")
        print("I'm passionate about coding and here are some of my details:")
        print(f"- Languages: {', '.join(self.languages)}")
        print(f"- Tools: {', '.join(self.tools)}")
        print(f"- Interests: {', '.join(self.interests)}")
        print(f"- Hobbies: {', '.join(self.hobbies)}")

# Create an instance of the SoftwareDeveloper class
developer = SoftwareDeveloper()
# Call the greet method
developer.greet()
```
