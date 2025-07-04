# 📌 POOBvsZOMBIES

> ⚠️ Estado: **En desarrollo**

Simulador inspirado en Plants vs Zombies desarrollado como proyecto final del curso de Programación Orientada a Objetos. Explora estrategias entre jugadores y máquinas con nuevos tipos de plantas, zombies, modos de juego y lógica de puntajes.

---

## 👥 Autores

SANTIAGO ROCHA DURAN y MARIA IRMA DIAZ ROZO
- JUAN SEBASTIÁN GUAYAZÁN CLAVIJO <juan.guayazan-c@mail.escuelaing.edu.co>

Programación Orientada a Objetos (ISIS POOB - 2 LEC y POOB-201 LAB)   
Decanatura Ingeniería de Sistemas → Centro de Estudios de Ingeniería de Software    
Ingeniería de Sistemas e Ingeniería Estadística    
Escuela Colombiana de Ingeniería Julio Garavito    
2024-2

## 🧠 Índice

- [📌 Nombre del Proyecto](#-poobvszombies)
- [🚀 Características](#-características)
- [⚙️ Tecnologías](#️-tecnologías)
- [📦 Instalación](#-instalación-y-requisitos)
- [▶️ Uso](#️-uso)
- [🧪 Pruebas](#-pruebas)
- [📁 Estructura del Proyecto](#-estructura-del-proyecto)
- [📌 TODOs / Funcionalidades Futuras](#-todos--funcionalidades-futuras)
- [👥 Autores](#-autores)
- [📄 Licencia](#-licencia)

---

## 🚀 Características

- ✅ Tres modos de juego: PvP, PvM, MvM
- ✅ Plantas y zombies personalizados (ECIPlant y ECIZombie)
- ✅ Sistema de recursos: soles y cerebros
- ✅ Persistencia de partidas y sistema de puntajes
- ✅ Interfaz gráfica amigable y adaptable
- ✅ Ideal para fines educativos, desarrollo de lógica y estrategia

---

## ⚙️ Tecnologías

- Lenguaje: `Java`
- Herramientas: `BlueJ`, `JUnit`, `PMD`, `Code Coverage`, `IntelliJ IDEA`
- Dependencias: JUnit 4, librerías estándar de Java

---

## 📦 Instalación y Requisitos

### Clonar el repositorio
```bash
git clone https://github.com/JuanSebastianGuayazanClavijoECI/POOBvsZOMBIES-POOB.git
```

### Requisitos

* Java 8+
* BlueJ, Eclipse o IntelliJ IDEA 
* JUnit 4+

### Instalación

1. Abrir el proyecto en BlueJ o importar como proyecto Java en Eclipse
2. Ejecutar las clases de la capa presentación o el simulador principal

---

## ▶️ Uso

> [!NOTE]\
> En BlueJ o Eclipse, ejecutar la clase Main o interfaz principal

> [!WARNING]\
> Asegurarse de que todos los recursos necesarios para la presentacion esten enunciados correctamente

---

## 🧪 Pruebas

```bash
javac -d bin src/domain/*.java src/presentation/*.java src/test/GameTest.java
```

---

## 📁 Estructura del Proyecto

```bash
📦 POOBvsZOMBIES-POOB
 ┣ 📂 src
 ┃ ┣ 📂 domain
 ┃ ┃ ┣ 📜 Attacking.java
 ┃ ┃ ┣ 📜 Basic.java
 ┃ ┃ ┣ 📜 Board.java
 ┃ ┃ ┣ 📜 Brainstein.java
 ┃ ┃ ┣ 📜 Buckethead.java
 ┃ ┃ ┣ 📜 Cell.java
 ┃ ┃ ┣ 📜 Character.java
 ┃ ┃ ┣ 📜 Conehead.java
 ┃ ┃ ┣ 📜 Defensive.java
 ┃ ┃ ┣ 📜 ECIPlant.java
 ┃ ┃ ┣ 📜 ECIZombie.java
 ┃ ┃ ┣ 📜 Evolve.java
 ┃ ┃ ┣ 📜 GameManager.java
 ┃ ┃ ┣ 📜 GameManagerMIvsMO.java
 ┃ ┃ ┣ 📜 GameManagerMIvsMS.java
 ┃ ┃ ┣ 📜 GameManagerMSvsMO.java
 ┃ ┃ ┣ 📜 GameManagerMSvsMS.java
 ┃ ┃ ┣ 📜 GameManagerPvsMO.java
 ┃ ┃ ┣ 📜 Generate.java
 ┃ ┃ ┣ 📜 Movement.java
 ┃ ┃ ┣ 📜 Pea.java
 ┃ ┃ ┣ 📜 Peashooter.java
 ┃ ┃ ┣ 📜 Plant.java
 ┃ ┃ ┣ 📜 POOBvsZOMBIESException.java
 ┃ ┃ ┣ 📜 PotatoMine.java
 ┃ ┃ ┣ 📜 Shovel.java
 ┃ ┃ ┣ 📜 Sunflower.java
 ┃ ┃ ┣ 📜 Support.java
 ┃ ┃ ┣ 📜 WallNut.java
 ┃ ┃ ┗ 📜 Zombies.java
 ┃ ┣ 📂 presentation
 ┃ ┃ ┣ 📂 resources
 ┃ ┃ ┃ ┣ 📂 images
 ┃ ┃ ┃ ┃ ┣ 📂 Fondos
 ┃ ┃ ┃ ┃ ┣ 📂 Nueva carpeta
 ┃ ┃ ┃ ┃ ┣ 📂 Objetos
 ┃ ┃ ┃ ┃ ┣ 📂 Pantallas
 ┃ ┃ ┃ ┃ ┣ 📂 Plantas 
 ┃ ┃ ┃ ┃ ┃ ┣ 📂 Modos
 ┃ ┃ ┃ ┃ ┃ ┗ 📂 Tarjetas
 ┃ ┃ ┃ ┃ ┣ 📂 Zombies
 ┃ ┃ ┃ ┃ ┃ ┣ 📂 Modos
 ┃ ┃ ┃ ┃ ┗ ┗ 📂 Tarjetas
 ┃ ┃ ┃ ┣ 📂 audio
 ┃ ┃ ┣ 📜 AudioManager.java
 ┃ ┃ ┣ 📜 Game.java
 ┃ ┃ ┣ 📜 GameMIvsMO.java
 ┃ ┃ ┣ 📜 GameMIvsMS.java
 ┃ ┃ ┣ 📜 GameMSvsMO.java
 ┃ ┃ ┣ 📜 GameMSvsMS.java
 ┃ ┃ ┣ 📜 GamePvsMO.java
 ┃ ┃ ┣ 📜 GamePvsMS.java
 ┃ ┃ ┣ 📜 PlantsMachines.java
 ┃ ┃ ┣ 📜 Select.java
 ┃ ┃ ┣ 📜 Start.java
 ┃ ┃ ┣ 📜 ZombieMachines.java
 ┃ ┃ ┗ 📜 ZombiePlantSelector.java          
 ┃ ┣ 📂 test
 ┃ ┗ ┗ 📜 GameTest.java
 ┣ 📂 bin
 ┃ ┣ 📂 domain
 ┃ ┗ 📂 presentation
 ┣ 📂 docs
 ┃ ┣ 📂 domain
 ┃ ┃ ┗ 📂 class-use
 ┃ ┣ 📂 presentation
 ┃ ┃ ┗ 📂 class-use
 ┃ ┣ 📂 legal
 ┃ ┣ 📂 class-use
 ┃ ┣ 📂 resource-files
 ┃ ┃ ┗ 📂 fonts
 ┃ ┗ 📂 script-files
 ┣ 📜 README.md
 ┣ 📜 .gitignore
 ┗ 📜 LICENSE
```
👉 [Diagrama de clases](./POOBvsZOMBIES.asta)
---

## 📌 TODOs / Funcionalidades Futuras

* [ ] Añadir sonidos y animaciones
* [ ] Mejorar interfaz gráfica con controles dinámicos
* [ ] Integrar un sistema de dificultad progresiva

---

## 📄 Licencia

Este proyecto está licenciado bajo propósitos académicos y educativos. Puedes consultar el archivo [LICENSE](./LICENSE) para más información.

---

