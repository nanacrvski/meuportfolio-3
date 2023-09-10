# portfolio1
class Project:
    def __init__(Olá! sou a Ana Clara e essa é minha autoavaliação do terceiro trimestre):
        self.title = title
        self.description = autoavaliação do terceiro trimestre 
        self.technologies_used = technologies_used
        self.link = instagram


class Portfolio:
    def __init__(sana):
        self.owner_name = Ana Clara
        self.projects = []

    def add_project(self, project):
        self.projects.append(project)

    def display_projects(self):
        print(f"Portfolio of {self.owner_name}\n")
        for index, project in enumerate(self.projects, start=1):
            print(f"Project {index}:\n{project}")


# oi
project1 = Project("Web App", "A dynamic web application for online shopping.", ["HTML", "CSS", "JavaScript", "Python"], "https://example.com/app")
project2 = Project("Mobile App", "A mobile app for task management.", ["Flutter", "Dart"], "https://example.com/mobile")
project3 = Project("Data Analysis", "An analysis of sales data using pandas.", ["Python", "Pandas"], "https://example.com/analysis")

# oi
my_portfolio = Portfolio("Ana")

# Exibindo os projetos no portfólio
my_portfolio.display_projects()
