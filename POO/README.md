<a name="readme-top"></a>

<br/>
<h3 align="center">Programación Orientada a Objetos</h3>
<p align="center">Trabajo Práctico Especial</p>

<details>
    <summary>Contenidos</summary>
    <ol>
        <li>
            <a href="#about-project">Acerca del proyecto</a>
            <ul>
                <li><a href="#lang-and-docs">Lenguajes y documentación utilizada</a></li>
                <li><a href="#pre-requisites">Pre-requisitos</a></li>
                <li><a href="#compile">Compilación</a></li>
                <li><a href="#run">Ejecución</a></li>
            </ul>
        </li>
        <li>
            <a href="#contents">Contenidos del programa</a>
        </li>
        <li>
            <a href="#contact">Contacto</a>
        </li>
    </ol>
</details>

<a name="about-project"></a>
## Acerca del proyecto

[![Paint POO 2C2022][paint-2c2022]](https://itba.edu.ar)

Este proyecto se desarrolló durante el segundo cuatrimestre del año 2022 para la materia Programación Orientada a Objetos.

<a name="lang-and-docs"></a>
### Lenguajes y documentación utilizada

* [![Java][Java-icon]][java-url]
Durante el desarrollo del proyecto se utilizó Java 8. <a href="https://docs.oracle.com/en/java/javase/17/docs/api/index.html">Java Docs</a>
* [![JavaFX][Javafx-icon]][javafx-url]
Durante el desarrollo del proyecto se utilizó el framework JavaFX <a href="https://openjfx.io/javadoc/19/">OpenJFX Docs</a>

<a name="pre-requisites"></a>
### Pre-requisitos

Para la compilación y ejecución del programa se requiere el descargar e instalar el Java Development Kit 8
* <a href="https://www.oracle.com/java/technologies/downloads/#java8-windows">Windows</a>
* <a href="https://www.oracle.com/java/technologies/downloads/#java8-mac">macOS</a>
* <a href="https://www.oracle.com/java/technologies/downloads/#java8-linux">Linux</a>


y la descarga de los módulos de JavaFX


* <a href="https://download2.gluonhq.com/openjfx/18.0.2/openjfx-18.0.2_windows-x64_bin-sdk.zip">Windows x64</a>
* <a href="https://download2.gluonhq.com/openjfx/18.0.2/openjfx-18.0.2_osx-x64_bin-sdk.zip">macOs x64</a>
* <a href="https://download2.gluonhq.com/openjfx/18.0.2/openjfx-18.0.2_linux-x64_bin-sdk.zip">Linux x64</a>


Posteriormente, se debe guardar el path de la carpeta lib, ubicada dentro del archivo descomprimido de OpenJFX. Por ejemplo,


```/home/your_user/Documents/javafx-sdk-18.0.2/lib```


y copiaremos en la clipboard los siguientes flags:


```--module-path PATH_GUARDADO --add-modules javafx.swt,javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media,javafx.swing,javafx.web```


, donde PATH_GUARDADO es el path guardado en la línea anterior.

<a name="compile"></a>
### Compilación

Para la compilación del programa, se debe descomprimir el archivo del proyecto, y ubicarse sobre la carpeta source, y ejecutar el siguiente comando:


```javac FLAGS_GUARDADOS frontend/AppLauncher.java```


<a name="run"></a>
### Ejecución

Para la ejecución del programa, se debe ejecutar el siguiente comando, ubicandose en la misma carpeta que el paso anterior:


```java FLAGS_GUARDADOS frontend/AppLauncher```


<a name="contents"></a>
## Contenidos del programa

En el desarrollo del programa, se implementaron las siguientes funcionalidades:
* Creación de figuras (cuadrado, rectángulo, círculo y elipse)
* Selección y movimiento de figuras
* Formateo de figuras (cambio de ancho de borde, cambio de color de borde, cambio de color interior)
* Copiar formato
* Invertir los ejes de una figura
* Copiar, cortar y pegar
* Deshacer y rehacer

<a name="contact"></a>
## Contacto

En caso de cualquier inconveniente, se puede comunicar a alguno de los colaboradores:


<a href="camuller@itba.edu.ar">catamuller</a>
<a href="tsmart@itba.edu.ar">tm-sm</a>
<a href="ncasella@itba.edu.ar">NCasella</a>
<a href="mquesada@itba.edu.ar">mquesada02</a>



[paint-2c2022]: https://github.com/mquesada02/project-resources/blob/main/POO/paint-resources/paint-2022.jpeg
[Java-icon]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white
[java-url]: https://www.java.com/es/
[Javafx-icon]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white
[javafx-url]: https://openjfx.io/
