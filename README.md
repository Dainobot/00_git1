@@ -24,6 +24,7 @@ git commit -m "mensaje del commit"
git commit --amend
git status
git log 
git checkout  -b *nombre rama nueva*
```

## Descargar repositorio de la nube
@@ -49,5 +50,21 @@ build/
*.jpg
```

## Ramas
```bash
git checkout  -b *nombre para la rama nueva*
git checkout *nombre de rama a la que queres cambiar*
git merge *nombre de la rama con la que se quiere fusionar*
```
### chekout -b

crea una rama nueva

### chekout

pasa a la rama que se desee

### merge

fusiona los archivos de dos ramas (en la que se usa y la que se especifica)