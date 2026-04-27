# Instalación de Compilador C y uso de `make`

En este trabajo se realizó la instalación de un compilador para el lenguaje C, se comprobó el funcionamiento del comando `make` y se muestran los resultados en un archivo `output.txt`.

---

## 1. Instalación del compilador

Se instaló el compilador mediante **MSYS2**, el instalador recomendado por Visual Studio Code.

Una vez instalado, se agregó el path de la ubicación del compilador a las variables de entorno del sistema, para poder reconocer sus comandos desde cualquier terminal.

![Configuración del PATH del compilador](https://github.com/user-attachments/assets/b88df431-8026-4ec3-a855-e3d192b1e6d8)

Luego, se verificó en la consola que el compilador esté correctamente instalado:

![Verificación en consola](https://github.com/user-attachments/assets/16f022b2-abb0-4fe9-8b44-8cd892195e86)

Por último, se instaló el comando `make` mediante Chocolatey:

```bash
choco install make
```

![Instalación de make](https://github.com/user-attachments/assets/fb48c559-7c29-46fc-a39b-cfd58914fb52)

---

## 2. Prueba inicial con `hello.c`

Una vez preparado el entorno, se escribió un programa `hello.c` para verificar que todo funcione correctamente:

![Código hello.c](https://github.com/user-attachments/assets/6dc03f07-a71a-4879-8be9-cbf45a6c72a2)

---

## 3. Configuración del `Makefile`

Se creó un `Makefile` que realiza las siguientes tareas de forma automática:

- Compila el programa
- Ejecuta el archivo compilado
- Genera el archivo `output.txt` con el resultado
- Muestra el contenido de `output.txt` en consola mediante el comando `type`

![Makefile](https://github.com/user-attachments/assets/0015d7ab-9984-42cf-9755-072be6723ef3)
