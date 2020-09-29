# Site généré  avec pelican 

## utilisation Local
### Génération du site
```console
pelican $path [-s settings.py]
```
### Publication du site 
```console
pelican content --debug --autoreload --output output --settings pelicanconf.py 
```
```console
pelican --listen
```
Accès local [http://localhost:8000/](http://localhost:8000/)

### Déploiement
```console
pelican content -s publishconf.py
```

