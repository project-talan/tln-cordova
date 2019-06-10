# Cordova skeleton application

## Getting started

### Attach to the existing project

* Add skeleton as subtree
```
git remote add tln-cordova https://github.com/project-talan/tln-cordova.git
git subtree add --prefix mobile/cordova-app tln-cordova master --squash
```
* Update to get latest version
```
git subtree pull --prefix mobile/cordova-app tln-cordova master --squash
```

### or Fork/clone repository

To develop standalone project, just clone repository or create fork using your account

## SDLC

| Command | Script | Description |
| ------- | ------ | ----------- |
| tln prereq | prereq.sh | Prepare local dev box configuration scripts |
