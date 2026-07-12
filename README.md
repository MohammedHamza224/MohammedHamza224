 [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&pause=1000&color=2B91AD&width=435&lines=Hi+there+%F0%9F%91%8B%2C+I'm+Mohammed+Hamza;Data+Analytics+Engineer+%7C+Ex.+Project+Manager;+I+work+with+Python%2C+SQL%2C+Power+BI%2C+and+Excel.;%F0%9F%92%BC+Open+to+Data+Analyst+Opportunities.)](https://git.io/typing-svg)
 

class DataProfessional:

    def __init__(self):
        self.name = "Mohammed Hamza"
        self.current_role = "Data Analyst"
        self.location = "Khobar, Saudi Arabia"
        self.languages = ["Arabic", "English"]

        self.about = (
            "Passionate Data Analyst with a background in IT Project Management "
            "and Business Intelligence. I enjoy transforming raw data into "
            "meaningful insights through analytics and interactive dashboards."
        )

        self.certifications = [
            "Microsoft Certified: Power BI Data Analyst Associate (PL-300)"
        ]

        self.currently_learning = [
            "Advanced SQL",
            "Python for Data Analysis",
            "Data Engineering",
            "Microsoft Fabric"
        ]

        self.skills = {
            "Programming": [
                "Python",
                "SQL"
            ],
            "Business Intelligence": [
                "Power BI",
                "DAX",
                "Power Query",
                "Tableau"
            ],
            "Data Analysis": [
                "Excel",
                "Pandas",
                "NumPy",
                "Matplotlib"
            ],
            "Databases": [
                "SQL Server"
            ],
            "Version Control": [
                "Git",
                "GitHub"
            ]
        }

    def say_hello(self):
        print(f"Hi 👋, I'm {self.name}")
        print(f"Role: {self.current_role}")
        print(self.about)
        print(f"Currently Learning: {', '.join(self.currently_learning)}")


me = DataProfessional()
me.say_hello()
