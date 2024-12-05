# Actividad: git add y Patrones

## Estructura Inicial del Proyecto

### 1. Crea la siguiente estructura de archivos y directorios:
```bash
mkdir -p proyecto-patrones/{docs,scripts,images,temp}
touch proyecto-patrones/{docs/{manual.txt,guia.md,readme.txt},scripts/{app.js,utils.py,config.js},images/{logo.png,icon.jpg,banner.gif},temp/{pruebas.log,debug.txt,draft.md}}
```
![image](https://github.com/user-attachments/assets/6228ea0f-de7c-4c51-be33-7f6ec48da902)

### 2. Verifica que la estructura es la siguiente:
```bash
tree proyecto-patrones/
```

![image](https://github.com/user-attachments/assets/d1711e28-f08c-4bbb-99f2-f0ce50ebbb31)

### 3. Inicializa el repositorio y haz un commit inicial:
```bash
git init
git commit -m "Primer commit"
```

![image](https://github.com/user-attachments/assets/4756568d-94a1-41a1-bafa-ef71d50896c6)

## COMENZAMOS
### 1. Prepara archivos con patrones simples
```bash
git add *.txt
git status
git commit -m "Ficheros txt"
```

![image](https://github.com/user-attachments/assets/0e9bb718-4bbe-4e57-b32b-b15194bf52e9)

![image](https://github.com/user-attachments/assets/399081f3-3788-44df-a0ae-2eba26d82f80)

### 2. Trabaja con subdirectorios y extensiones
```bash
git add *.js
git status
git reset config.js
git status
```

![image](https://github.com/user-attachments/assets/a58bcec0-fbeb-4cab-83d8-896c223701fa)

```bash
git commit -m "Fichero app.js"
```
![image](https://github.com/user-attachments/assets/f75c646e-e032-4261-9489-f2fc615b0828)

### 3. Máscaras en niveles
```bash
git add .
git reset *.gif
git status
```
![image](https://github.com/user-attachments/assets/8b3a66df-f7ac-4e3e-97dc-3f5af1eaeed9)

```bash
git commit -m "Imagenes añadidas"
```
![image](https://github.com/user-attachments/assets/6a94eddc-9ea8-4dc7-bab3-fb2ca3f75599)

### 4. Sube el repositorio Git Local al Remoto
```bash
git remote add BonamusaMarcPractExtra2425 https://github.com/MarcBonamusa/BonamusaMarcPractExtra2425.git
```
![image](https://github.com/user-attachments/assets/7df9c215-7c0d-4e77-a0a2-bc0ead83c78b)

```bash
git push BonamusaMarcPractExtra2425 master
```
![image](https://github.com/user-attachments/assets/ee4426fd-33cd-4798-a88d-2d4b21596869)


