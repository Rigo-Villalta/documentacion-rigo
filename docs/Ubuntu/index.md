# Referencia Ubuntu

Referencia de comandos más usados en Linux en general y Ubuntu en particular

Se puede ver la [documentación oficial de ubuntu](https://documentation.ubuntu.com/server/) para más información

## Usuarios

```bash title="Crear usuarios"
sudo adduser username
```

```bash title="Activar el usuario sudo"
sudo passwd #(1)!
```

1. El prompt preguntará por la contraseña para sudo


```bash title="Cambio de contraseña de un usuario"
sudo passwd username #(1)!
```

1. El prompt preguntará por la contraseña para el usuario