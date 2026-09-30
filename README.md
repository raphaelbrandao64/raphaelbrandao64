    class Developer:
        def __init__(self, name, age, education, language):
            self.name = name
            self.age = age
            self.education = education
            self.language = language
            self.status = "Learning & building"
    
        def code(self):
            return f"Converting coffee and logic into {self.language} code... 🐍"
    
        def __str__(self):
            return f"{self.name} | {self.language} Developer"
    
    
    raphael = Developer(
        name="Raphael Brandão Silva",
        age=16,
        education="Técnico em Informática — IFBA (2º ano)",
        language="Python"
    )
    
    print(raphael)
    print(raphael.code())
