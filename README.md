```python
class Person:
  name = "raul",
  age = 17,
  whatIDo = ["Pentest","Back-end Devoloper"],
  web = {
    "front-end": {
      "langs": ["javascript", "typescript"],
      "frameworks": ["angular", "ionic"]
    },
    "back-end": {
      "langs": ["javascript","java","SQL"],
      "frameworks": ["spring","express"]
    }
  }
  tech = ["linux","git","python","C","bash script"],
  likeToDo = ["roblox","CTF"]
  
  def __str__(self):
    return f"{self.name}{self.age}{self.web}{self.tech}{self.likeToDo}"

raul = Person()
print(raul)
```
