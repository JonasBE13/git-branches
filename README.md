# git-branches

Vi lägger till första raden och committar


# instructions branch

Nu skapar vi en brancch som heter instructions. Dertta gör vi mha kommandot

```md
git checkout -b instructions
```

För att pusha upp ändringar till denna branch behöver vi först stage, commit och pusha. För push till denna branch gör vi

```md
git push origin instructions
```

För att checka branches som vi har:

```md
git branch
```

# Pull requests

För att få mergea in ändringar från denna branch in till main så öppnar vi en pull request. Detta gör vi i fliken pull request. 

<img src="assets/pull_request.png" width = 400>

<<<<<<< HEAD
---
## Merge

Efter pull request är det viktigt att varje person kör en pull till sin main branch och pull till sin egna branch.
=======
## Merging

Detta ska skapa en konflikt!!
>>>>>>> 37fe3c8ea2ed2c7ee210e91b2a67ef1e35f0ab95
