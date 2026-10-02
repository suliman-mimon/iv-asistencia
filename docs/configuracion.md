# Configuración del repositorio

## Identidad de Git

Comprobada con `git config user.name` y `git config user.email`:

```text
Suliman
suliman.mimon@gmail.com
```

## Acceso a GitHub mediante SSH

Clave pública generada con `ssh-keygen -t ed25519 -C "suliman-github" -f ~/.ssh/suliman-github` y registrada en GitHub con `gh ssh-key add ~/.ssh/suliman-github.pub --title "Suliman GitHub SSH" --type authentication`.

Se añadió una entrada `Host github.com` en `~/.ssh/config` que selecciona esta clave:

```text
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/suliman-github
```

## Herramientas

`git-iv` está instalado en `~/.local/bin/git-iv` y responde a `git iv`.
