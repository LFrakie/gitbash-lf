# INSTALATION

## MODO standar
Agregamos la carpeta entera con todos los comandos al PATH en nuestro **.bashrc**.

```bash
PATH="$PATH:$HOME/lift/gitbash-lf"
export PATH
```

Ejem: 

PATH="$PATH:/rutaDondeTenemosNuestro/gitbash-lf"
export PATH

### MODO 1  (uno por uno)

Ejemplos:
```bash
ln -s /root/dev-lfrakie/proyectos/gitbash-lf/git-up /usr/bin/git-up
```

O tmbn asi:

```bash
ln -s $PWD/git-up
```

### MODO 2 (Agregando la carpeta entera con todos los comandos al PATH)

```bash
PATH="$PATH:/rutaDondeTenemosNuestro/gitbash-lf"
export PATH
```
