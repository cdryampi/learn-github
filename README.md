# learn-github

Repositorio para aprender Github paso a paso.

Crea un `Fork` para contribuir, más información: [cómo contribuir a este repositorio](CONTRIBUTING.md).

---

## Índice

- [Ejercicio 1](#ejercicio-1)

---

### Ejercicio 1

1. Vamos a imaginar que trabajamos en un libro sobre Git y queremos hacer algunos temas. Se va a trabajar en ramas para cada capítulo. Implementa las siguientes **ramas** con al menos un archivo y un commit con cualquier contenido:

- `introduccion` -> intro.txt, intro.md...
- `capitulo01` -> capitulo01.txt...
- `capitulo02` -> capitulo02.txt...

Finalmente, vamos a fusionar todos estos contenidos en `libro`. El resultado debe ser algo como:

```
intro.txt
capitulo01.txt
capitulo02.txt
etc.
```

- `git log` debe mostrar los commits de cada rama más el commit de merge.

2. resolución

```bash
git checkout -b introduccion
echo "introduccion" > intro.txt
git add intro.txt
git commit -m "introduccion"
git checkout -b capitulo01
echo "capitulo01" > capitulo01.txt
git add capitulo01.txt
git commit -m "capitulo01"
git checkout -b capitulo02
echo "capitulo02" > capitulo02.txt
git add capitulo02.txt
git commit -m "capitulo02"
git checkout introduccion
git merge capitulo01
git merge capitulo02

```

3. Resultado del `git log --oneline`
   3.1 ![Resultado del git log](./src/img/ejercicio1.png)

---
