# Referencia de mkdocs

[Sitio oficial de Mkdocs](https://squidfunk.github.io/mkdocs-material/)

[Referencia en github](https://github.com/squidfunk/mkdocs-material/tree/master/docs/reference) con muchos ejemplos en markdown, para ver el código fuente ver la pestaña "code" de cada archivo.

## Comandos útiles
Los siguientes comandos están en el contexto de mkdocs, es decir que debemos tener activato el entorno virtual de Python en que mkdocs este instalado


```bash title="Servidor de desarrollo"""
mkdocs serve # (1)!
```

1. Se corre el servidor de desarrollo con actualización automática en el navegador

```bash title="Generar archivos estáticos"""
mkdocs build --clean # (1)!
```

1. Se reconstruyen los archivos estáticos del sitio, el flag "--clean" borra cualquier caché

```bash title="Publicar en github pages"""
mkdocs gh-deploy --clean # (1)!
```

1. Se contruyen los archivos estáticos actualizados a la rama de github pages, por convención esto hará que los cambios se publiquen luego de que se haga el push, el flag "--clean" borra cualquier caché
