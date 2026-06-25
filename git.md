# Git

## Comandos básicos

### git status

Muestra cambios pendientes y el estado del repositorio.

```bash
17:58 $ git status
En la rama main
Tu rama está actualizada con 'origin/main'.

Cambios no rastreados para el commit:
  (usa "git add <archivo>..." para actualizar lo que será confirmado)
  (usa "git restore <archivo>..." para descartar los cambios en el directorio de trabajo)
	modificados:     notas_nuevas.md

sin cambios agregados al commit (usa "git add" y/o "git commit -a")
```

### git add

Agrega cambios al área de preparación para el commit.

```bash
18:11 $ git add notas_nuevas.md 
```

### git commit

Confirma los cambios en el repositorio.

```bash
18:11 $ git commit -m "Algunas notas"
[main 63831a7] Algunas notas
 1 file changed, 14 insertions(+), 1 deletion(-)
```

### git push

Sube los cambios al repositorio remoto.

```bash
18:11 $ git push origin 
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 12 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 1023 bytes | 1023.00 KiB/s, listo.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:simomocchiutti/Primer-Repositorio.git
   2bf4ff6..63831a7  main -> main
```
