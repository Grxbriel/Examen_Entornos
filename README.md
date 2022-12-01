# Examen Entornos

## Practica 1

Desde el escritorio con el comando `mkdir Examen_Entornos` creamos la carpeta y desde ella iniciamos un repositorio con `git init` 

<img width="632" alt="Captura de pantalla 2022-12-01 a las 17 49 12" src="https://user-images.githubusercontent.com/87373226/205115886-f65f8aef-2496-4c09-b8a9-1791454fcb35.png">

Lo subimos al repositorio local con:

~~~
git remote add origin <enlace>
git branch -m main
git push -u origin main
~~~

<img width="851" alt="Captura de pantalla 2022-12-01 a las 18 00 11" src="https://user-images.githubusercontent.com/87373226/205115898-a71e495d-fcc5-439a-a336-7b50a01b859d.png">

Creamos el README.md con el `touch README.md` y lo subimos con :

~~~
git add .
git commit -m "Primer Commit"
git push
~~~

<img width="685" alt="Captura de pantalla 2022-12-01 a las 18 08 06" src="https://user-images.githubusercontent.com/87373226/205115908-a14c2723-a8eb-453c-986f-ed516778ab53.png">


## Practica 2

### 1- Con el `git log --oneline --all` visualizamos nuestros commits

<img width="503" alt="Captura de pantalla 2022-12-01 a las 18 19 32" src="https://user-images.githubusercontent.com/87373226/205118200-d42af376-ef64-49fa-bc39-46dbeeb4d809.png">

<img width="345" alt="Captura de pantalla 2022-12-01 a las 18 24 05" src="https://user-images.githubusercontent.com/87373226/205120074-aa8839b9-81d4-470c-9d02-04cd34fbbadb.png">

### 2- Nos movemos por los commits y vemos sus cambios

Como podemos ver tenemos varios commits, vamos a trabajar sobre los tres ultimos commits del Readme

Ahora nos movemos al commit Readme 1 y vemos su contenido con:

~~~
git checkout 6368
cat README2.md
~~~

<img width="573" alt="Captura de pantalla 2022-12-01 a las 18 28 57" src="https://user-images.githubusercontent.com/87373226/205120373-190815dc-a8f4-44ac-a700-991e18426fb5.png">

Vemos con el `git log --oneline --all` que nos encontramos en el primer commit del Readme

<img width="322" alt="Captura de pantalla 2022-12-01 a las 18 30 33" src="https://user-images.githubusercontent.com/87373226/205120675-2f81d363-d4ff-41a7-a8f7-5532a5fd4129.png">

### 3- Nos movemos al segundo commit

Con el `git checkout ef68` nos vamos el segundo commit y repetimos el proceso para ver que contiene el README2.md, despues con el `git log --oneline --all` vemos que nos encontramos en el segundo.

<img width="508" alt="Captura de pantalla 2022-12-01 a las 18 33 23" src="https://user-images.githubusercontent.com/87373226/205121272-3e5728ec-c2fb-4b26-93fb-f148ce6121da.png">


<img width="314" alt="Captura de pantalla 2022-12-01 a las 18 33 47" src="https://user-images.githubusercontent.com/87373226/205121360-00f4683e-bed0-47b8-9c4f-fa6755856682.png">

### 4- Finalmente con el `git checkout main` volvemos al commit actual

<img width="495" alt="Captura de pantalla 2022-12-01 a las 18 36 08" src="https://user-images.githubusercontent.com/87373226/205121765-61f738d6-72bf-442d-b7d8-965784f30dc2.png">

Comprobamos con el `git log --oneline --all` que ya estamos en la actual

<img width="481" alt="Captura de pantalla 2022-12-01 a las 18 19 22" src="https://user-images.githubusercontent.com/87373226/205121823-0382847f-fe3a-4189-a46d-6d6d82b60b76.png">





