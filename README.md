
<h2> Hi, I'm Jake Baggs! <img src="https://media.giphy.com/media/l0MYDEPLWRWbJoRuU/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/YST1Ffp9hIFNaH7OiR/giphy.gif" width="120">
<p><em>SRE at Alteryx <img src="https://media.giphy.com/media/4FQMuOKR6zQRO/giphy.gif" width="30"></br>Grad Student<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>
[![Linkedin:jacob baggs](https://img.shields.io/badge/-jacobbaggs-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jacob-baggs-41a00485/)](https://www.linkedin.com/in/jacob-baggs-41a00485/)
[![GitHub JacobBaggs](https://img.shields.io/github/followers/thaiane?label=follow&style=social)](https://github.com/jbaggs62)
### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...  
```python
from __future__ import annotations
import json
from dataclasses import asdict, dataclass
@dataclass
class about_me:
    languages: tuple[str, ...] = ("Python", "Java", "Rust", "Go")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "DynamoDB", 
                                  "Cassandra", "DB2", "MongoDB")
    technologies:      tuple[str, ...] = ("Docker", "Kubernetes", "DVC", 
                                          "Git", "SQS","AWS","GitOps")
    hobbies:      tuple[str, ...] = ("BJJ", "Keyboards", "Gaming", "Crypto")

    def jsonify(self):
        return json.dumps(asdict(self), indent=4)
jake = about_me()
print(jake.jsonify())
```
<!---
jbaggs62/jbaggs62 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 
