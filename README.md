# Aplicación HolaMundo en Node.js
## Pasos manuales de instalación de node para replicarlos en el servidor.

Iniciamos instalando nvm

```

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

```

Comprobamos si se instalo comprobando la versión:

```
nvm -v
```

