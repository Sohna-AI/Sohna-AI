## Hi there 👋

```js
class Sohna_Ai:

    def __init__(self):
        self.username = 'Sohna-AI'
        self.name = 'Pushpinder Singh'
        self.position = 'Software Developer'
        self.portfolio = 'https://sohna-ai.github.io/'
        self.projects = 'https://sohna-ai.github.io/projects.html'
        self.resume = 'https://sohna-ai.github.io/resume.html'
        self.linkedIn = 'https://www.linkedin.com/in/pushpinder-s-03219b125/'
        self.code = {
            'backend': ['Python', 'Flask',  'NodeJS', 'ExpressJS'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3'],
            'devops': ['Docker', 'GitHub Actions', 'AWS'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS'],
            'tools': ['GIT', 'GitHub', 'SQLAlchemy', 'Sequelize'],
            'misc': ['CRUD', 'RESTful', 'TDD', 'SCRUM']
        }
        self.hobbies = {
            'Favorite video games': ['Mario games', 'Call of duty', 'GTA', 'Dokkan'],
            'Sports': ['Basketball', 'Bowling', 'Football'],
            'Anime': ['One Piece', 'Black Clover', 'Seven Deadly Sins', 'Dragon Ball',
                      'My Hero Academia', 'Full Metal Alchemist', 'Hunter X Hunter',
                      'Demon Slayer', 'Spy X Family', 'Assassination Classroom'],}

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = Sohna_Ai()
    print(me)
```

