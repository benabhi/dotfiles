# dotfiles

Agregar a la variable path la siguiente ruta: `~/.local/bin`.

```
export PATH=$PATH:/home/benabhi/.local/bin
```

Ejecutar el siguiente comando instala, incicializa y clona el repo.

```
sh -c "$(curl -fsLS get.chezmoi.io/lb)" -- init --apply benabh
```

tada!
