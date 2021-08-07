# Trukos Github y PIP

```
pip freeze > requirements.txt
pip install -r requirements.txt
```

ver diferencias
```
git diff
```

ver lo modificado en un commit
```
git show <COMMIT>
```

ver lo que tenemos local
```
git status
```

ver rama
```
git branch
```

Crear una rama
```
git checkout -b branchname
```

Eliminar una rama
```
git checkout -d branchname
```

Unir Rama
```
git checkout master
git merge branchname
```

ver el log
```
git log -3
```
```
git log -5 --pretty=oneline
```

Descartar los cambios. Regresa todo al último commit de la rama
```
git reset --hard
```
