    class Developer:
        def __init__(self, name, age, education, language):
            self.name = name
            self.age = age
            self.education = education
            self.language = language
            self.status = "Learning & building"

        def __str__(self):
            return f"{self.name} | {self.language} Developer"


    Raphael = Developer(
        name="Raphael Brandão Silva",
        age=16y,
        education="Técnico em Informática — IFBA - 2º ano",
        language="Python"
    )
    
    print(Raphael)
