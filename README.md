# GraalLatino 🚀

**GraalLatino** es una implementación de alto rendimiento del lenguaje de programación **Latino** (un lenguaje de código abierto diseñado para hispanohablantes con sintaxis en español), desarrollada sobre **GraalVM** utilizando el framework Truffle.

Esta plataforma lleva la sintaxis intuitiva de Latino al entorno de ejecución empresarial de GraalVM, ofreciendo compilación JIT (Just-In-Time) avanzada, ejecución nativa de alta velocidad e interoperabilidad directa con el ecosistema políglota de la JVM.

---

## 🌟 Características Principales

* **Sintaxis en Español con Alto Rendimiento:** Escribe código utilizando construcciones naturales en español (`si`, `mientras`, `funcion`, `imprimir`) respaldado por el motor de optimización de GraalVM.
* **Compilación JIT Avanzada:** Optimización dinámica en tiempo de ejecución (inlining, *escape analysis*, deoptimización) sobre el AST de Truffle para ejecutar algoritmos a alta velocidad.
* **Interoperabilidad Políglota:** Accede y comparte objetos con Java, Python, JavaScript, R y C/C++ directamente sin sobrecarga de serialización.
* **Binarios Nativos (Native Image):** Compila programas en Latino directamente a ejecutables binarios autónomos con **GraalVM Native Image** para tiempos de arranque instantáneos y mínimo uso de memoria.

---

## 🏗️ Arquitectura de la Plataforma

* **Latino Truffle Parser:** Transforma la sintaxis y gramática en español de Latino en un Árbol de Sintaxis Abstracta (AST) optimizado para Truffle.
* **GraalVM Runtime Engine:** Motor de ejecución que gestiona los tipos dinámicos de Latino y aplica compilación JIT sobre los bloques de código más frecuentados.
* **Polyglot Interop API:** Interfaz para invocar librerías externas de la JVM o enviar estructuras de datos de Latino a otros lenguajes en tiempo de ejecución.

---

## 🚦 Inicio Rápido

### Prerrequisitos

* **GraalVM JDK** (versión 21 o superior) con soporte para Truffle.
* Variable de entorno `JAVA_HOME` configurada hacia la instalación de GraalVM.

### Instalación

```bash
# Clonar el repositorio
git clone [https://github.com/tu-usuario/graallatino.git](https://github.com/tu-usuario/graallatino.git)
cd graallatino

# Construir el proyecto utilizando Gradle
./gradlew build
