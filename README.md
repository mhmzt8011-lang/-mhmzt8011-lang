class DataScientist:
    def __init__(self, name, pronouns, fields, tools, algorithms, community):
        self.name = name
        self.pronouns = pronouns
        self.fields = fields
        self.tools = tools
        self.algorithms = algorithms
        self.community = community

    def introduce(self):
        print(f"Hi, I'm {self.name}! Passionate about turning data into actionable insights.")

#  Data Science
thai_ds = DataScientist(
    name="Mahmoud Hamza",
    pronouns=["she", "her"],
    fields=["Data Science", "Machine Learning", "Deep Learning", "Data Engineering"],
    code=["Python", "Java", "C++", "SQL", "R"],
    tools=["Pandas", "NumPy", "Scikit-Learn", "TensorFlow", "PyTorch", "Docker", "Apache Spark"],
    algorithms=["Linear Regression", "Random Forests", "Neural Networks", "Gradient Boosting"],
    community={
        "coorganizer": "AfroPython",
        "speaker": "Latinity",
        "mentor": "EducaTRANSforma"
    }
)

thai_ds.introduce()
