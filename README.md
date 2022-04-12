# poao-meta
Inneholder oversikt over repositories brukt av po-arbeidsoppfolging

## Hvordan bruke

### instaler første gang
installer
```bash
npm i -g meta
meta git clone https://github.com/navikt/poao-meta.git
```


### Oppdatere etter andre har lagt til nye repoer
```bash
# get new .meta file
git pull origin main

# clone missing projects
meta git update
```


### Legge til nye repositorier
```
meta project import [team]/[project] [repo url]
```

### Meta
https://github.com/mateodelnorte/meta
