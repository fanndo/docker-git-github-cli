
# Proyecto Docker/Ubuntu

## Contenedor Ubuntu con Git/Github

Proyecto prueba para integrarme con git y github. 


## Ejecutar

```docker componse
docker compose up --build
```
## Ingresar con modo interactivo

```docker componse
docker exec -it container-name bash
```
## Configurar GIT 

### Configurar usuario y correo
```configurar correo
git config --global user.email 'tumail@example.com'
```
```configurar usuario
git config --global user.name 'tu nombre'
```
## Configurar Github CLI 

### Autenticación GitHub CLI
```autenticacion en Github cli
 gh auth login
```

## Creacion de Clave ssh (opcional)

#### Generar Clave ssh

```Generar Clave ssh
  ssh-keygen -t rsa -b 4096 -C "youremail@example.com"
```

#### Comprobar proceso y agregarlo

```Comprobar proceso (Windows/Git Bash)
 eval $(ssh-agent -s)
```
```agregarlo (Windows/Git Bash)
 ssh-add ~/.ssh/id_rsa
```
