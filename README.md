# poao-meta
Inneholder oversikt over repositories brukt av po-arbeidsoppfolging

Meta er et verktøy for å håndtere flere git repositories.  
Det hjelper oss med å clone og holde orden på alle repositoriene våre

### Setup

```bash
# installer meta
npm i -g meta
# clone poao meta og alle under repositorine
meta git clone https://github.com/navikt/poao-meta.git
```


### Oppdatere etter andre har lagt til nye repoer
```bash
# get new .meta file
git pull origin main

# clone missing projects
meta git update
```


### Nye repositorier
For å legge til repositories i repoet må man kjøre komandoen under.

```
meta project import [team]/[project] [repo url]
```

Vi bruker https lenker for repositorien våre
eksempel for og legge til aktivitesplan:
```bash
meta project import dab/aktivitetsplan https://github.com/navikt/aktivitetsplan.git
```

## Meta
[Les mer om meta](https://github.com/mateodelnorte/meta)


## Feil
vanlige feil.
- Får ikke lastet inn alle repositoriene eller får ikke pushet
  - installer gh cli og kjør gh auth login med default valg. 