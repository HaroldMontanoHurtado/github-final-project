Tarea 3: Revierta el error tipográfico y envíe una solicitud de extracción
```
theia@theia-haroldandre1:/home/project/mcino-Introduction-to-Git-and-GitHub$ curl -s https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/12696 | jq -r '.head.repo.clone_url'
https://github.com/HaroldMontanoHurtado/mcino-Introduction-to-Git-and-GitHub.git
```
