# portfolio1
class Project:
    def __init__(self, title, description, technologies_used, link):
        self.title = title
        self.description = Portfólio de matmática do Anthony. 
        self.technologies_used = technologies_used
        self.link = a

    def __str__(self):
        return f"Project: {self.title}\nDescription: {self.description}\nTechnologies Used: {', '.join(self.technologies_used)}\nLink: {self.link}\n"


class Portfolio:
    def __init__(self, owner_name):
        self.owner_name = Anthony 
        self.projects = []

    def add_project(self, project):
        self.projects.append(project)

    def display_projects(self):
        print(f"Portfolio of {self.owner_name}\n")
        for index, project in enumerate(self.projects, start=1):
            print(f"Project {index}:\n{project}")


# Criando instâncias de projetos
project1 = Project("Web App", "A dynamic web application for online shopping.", ["HTML", "CSS", "JavaScript", "Python"], "https://example.com/app")
project2 = Project("Mobile App", "A mobile app for task management.", ["Flutter", "Dart"], "https://example.com/mobile")
project3 = Project("Data Analysis", "An analysis of sales data using pandas.", ["Python", "Pandas"], "https://example.com/analysis")

# Criando uma instância do portfólio
my_portfolio = Portfolio("Anthony")

# Adicionando projetos ao portfólio
my_portfolio.add_project(project1)
my_portfolio.add_project(project2)
my_portfolio.add_project(project3)

# Exibindo os projetos no portfólio
my_portfolio.display_projects()
