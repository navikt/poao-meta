# poao-meta
Inneholder oversikt over repositoris brukt av po-arbeidsoppfolging

## Hvordan bruke

### instaler første gang
installer meta
`npm i -g meta`

### Oppdatere etter andre har lagt til nye repoer
```bash
# get new .meta file
git pull origin master

# clone missing projects
meta git update
```


### Legge til nye repositorier
```
meta project import [team]/[project] [repo url]
```

### Meta
https://github.com/mateodelnorte/meta
