```python
class Developer:
    def __init__(self):
        self.name = "Raphael Brandão Silva"
        self.age = 16
        self.role = "IT Student & Python Enthusiast"
        self.education = "Technical High School in IT @ IFBA (2nd Year)"
        self.main_language = "Python"
        
    def get_status(self):
        return "Learning, building projects, and evolving every day! 🚀"

me = Developer()
print(me.get_status())
