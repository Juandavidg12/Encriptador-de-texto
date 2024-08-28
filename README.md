# Encriptador de Texto

Este es un proyecto simple de encriptador de texto creado con HTML, CSS y JavaScript. Permite encriptar y desencriptar mensajes utilizando un sistema de sustitución de caracteres. También puedes copiar el texto encriptado o desencriptado al portapapeles para utilizarlo en otras aplicaciones.

## Tabla de Contenidos

- [Características](#características)
- [Llaves de Encriptación](#llaves-de-encriptación)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)

## Características

- **Encriptar Texto**: Convierte un mensaje ingresado en un texto cifrado utilizando un conjunto específico de reglas de sustitución.
- **Desencriptar Texto**: Convierte el texto cifrado de vuelta a su forma original utilizando las mismas reglas.
- **Copiar Texto**: Permite copiar el texto encriptado o desencriptado al portapapeles.
- **Interfaz Simple**: Interfaz de usuario amigable con un diseño limpio y minimalista.

## Llaves de Encriptación

Las "llaves" de encriptación que utilizamos son las siguientes:

- La letra **"e"** se convierte en **"enter"**
- La letra **"i"** se convierte en **"imes"**
- La letra **"a"** se convierte en **"ai"**
- La letra **"o"** se convierte en **"ober"**
- La letra **"u"** se convierte en **"ufat"**

Por ejemplo, la palabra **"hola"** se encriptaría como **"hoberlai"**.

## Requisitos

Este proyecto no requiere ninguna instalación adicional de dependencias ni configuraciones específicas. Solo necesitas un navegador web moderno para ejecutar el código.

## Instalación

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu-usuario/encriptador-de-texto.git
    ```

2. Abre el archivo `index.html` en tu navegador web preferido.

Eso es todo. ¡Ahora puedes comenzar a encriptar y desencriptar mensajes!

## Uso

1. Ingresa el texto que deseas encriptar en el área de texto.
2. Haz clic en el botón **Encriptar** para transformar el texto utilizando las reglas de encriptación.
3. Si deseas revertir el proceso, haz clic en el botón **Desencriptar**.
4. Para copiar el texto encriptado o desencriptado, simplemente haz clic en el botón **Copiar Texto**.

## Estructura del Proyecto

```bash
encriptador-de-texto/
│
├── img/
│   └── 1.png                # Imagen predeterminada
│   └── encriptado.png       # Imagen que se muestra al encriptar
│   └── desencriptar.png     # Imagen que se muestra al desencriptar
│
├── styles.css               # Archivo de estilos CSS
├── Script.js                # Archivo JavaScript con la lógica de encriptado, desencriptado y copia
└── index.html               # Archivo HTML principal
