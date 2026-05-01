# 📘 Curso de Flutter — De cero a PRO

> Ruta progresiva para aprender Dart y Flutter entendiendo código, interfaz,
> estado, renderizado y comportamiento real de una app móvil.

**Repositorio en GitHub:** https://github.com/yetsin7/Curso-de-Flutter

---

## 🇳🇮 Para estudiantes de Nicaragua (y de toda Latinoamérica)

Hola, soy Yetsin, programador nicaragüense. Este libro lo escribí pensando
primero en ti: el estudiante, el autodidacta, el joven curioso de Managua,
León, Estelí, Matagalpa, Granada, Bluefields o cualquier rincón de Nicaragua
que quiere aprender a programar y no tiene cómo pagar un curso caro.

Si estás en Centroamérica, México, Sudamérica o cualquier país de habla
hispana, también es para ti. El contenido está pensado en español neutro
para que cualquier persona pueda seguirlo sin problema.

No necesitas registrarte, no necesitas pagar nada, no necesitas internet
permanente. Solo clona el repositorio, abre tu editor y empieza a programar.

---

## 🎯 ¿Por qué existe este libro?

En Nicaragua hay mucho talento joven con ganas de aprender programación,
pero los recursos serios suelen estar en inglés, cuestan caros o requieren
internet estable que no siempre tenemos. Este libro existe para cambiar eso.

La misión es simple:

- Que **más nicaragüenses** puedan aprender a programar de verdad.
- Que **no haga falta dinero** para empezar una carrera en tecnología.
- Que se pueda estudiar **sin internet permanente** una vez clonado el repo.
- Que **no se pidan requisitos previos** ni títulos ni cursos pagados.
- Que el contenido esté **en español** y con calidad profesional.

Si este libro te ayuda a conseguir tu primer trabajo como desarrollador,
a crear tu primera app, o simplemente a entender cómo funciona el software,
ya cumplió su propósito.

---

## ✅ ¿Qué obtienes con este repositorio?

- 100% **gratuito**, sin registro y sin anuncios.
- Funciona **offline** una vez clonado.
- Explicaciones detalladas en **comentarios en español**.
- Código real que puedes ejecutar en tu computadora.
- Múltiples formas de resolver el mismo problema.
- Ejercicios prácticos con soluciones.
- Inspirado en el estilo del **Curso de Python** del mismo autor, pero
  enfocado completamente en el ecosistema **Dart/Flutter**.

---

## 👥 ¿Para quién es?

Para **cualquier persona** que quiera aprender Flutter y Dart:

- Estudiantes universitarios o de secundaria que empiezan desde cero.
- Autodidactas que aprenden por su cuenta sin un instructor.
- Programadores que ya saben otro lenguaje (Python, JavaScript, Java, etc.).
- Desarrolladores Flutter que quieren reforzar sus bases en Dart.
- Cualquiera con ganas de practicar y curiosidad por entender cómo funciona
  una app por dentro.

No se requiere experiencia previa con Flutter. Solo ganas de aprender.

---

## 🧠 Qué vas a entender sobre software y hardware

Este libro insiste en una idea muy importante: una app no es solo pantallas.
Una app es un sistema que:

- recibe eventos del usuario desde el hardware táctil, teclado o red;
- procesa lógica en CPU;
- guarda datos en memoria RAM o almacenamiento local;
- vuelve a dibujar la interfaz en pantalla;
- administra estados, tiempos y recursos.

Cuando aprendes Flutter con esta mirada, dejas de memorizar widgets y
empiezas a entender el comportamiento real de la aplicación.

---

## ⚙️ Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

| Herramienta | Dónde obtenerla |
|-------------|----------------|
| **Flutter SDK** (3.x o superior) | https://flutter.dev/docs/get-started/install |
| **Dart SDK** (incluido con Flutter) | Viene con Flutter automáticamente |
| **VS Code** o **Android Studio** | https://code.visualstudio.com/ |
| **Extensión Flutter** para VS Code | Buscar "Flutter" en el Marketplace de VS Code |

Verifica que todo esté instalado correctamente:

```bash
flutter doctor
dart --version
```

> Consejo: si tu internet es lento o intermitente, descarga el Flutter SDK
> una sola vez y guárdalo. Una vez instalado, puedes estudiar y compilar
> sin necesidad de conexión.

---

## 🚀 Cómo usar este repositorio

Primero, clona el repositorio:

```bash
git clone https://github.com/yetsin7/Curso-de-Flutter.git
cd Curso-de-Flutter
```

### Módulos de Dart puro (01–11)

Los archivos `.dart` se ejecutan directamente desde la terminal:

```bash
dart run 01_hola_mundo.dart
```

No necesitas crear un proyecto Flutter. Son archivos Dart puros, ideales
para aprender el lenguaje.

### Módulos de Flutter UI (12–19)

Estos módulos contienen proyectos Flutter completos. Para ejecutarlos:

```bash
cd 12-widgets-basicos/proyecto/
flutter run
```

### Orden recomendado

Lee los módulos **en orden numérico**. Primero domina Dart; luego pasa a
Flutter UI; después estudia arquitectura, persistencia, i18n y testing.

---

## 📚 Estructura del libro

### 🟢 Nivel Básico — Fundamentos de Dart (Módulos 01–11)

| Módulo | Tema | Descripción |
|--------|------|-------------|
| 01 | Fundamentos de Dart | Variables, tipos, hola mundo, comentarios, constantes |
| 02 | Operadores | Aritméticos, comparación, lógicos, asignación |
| 03 | Control de flujo | if/else, switch, for, while, break/continue |
| 04 | Funciones | Declaración, parámetros, retorno, arrow, closures |
| 05 | Colecciones | List, Map, Set, Iterable, generators |
| 06 | Null Safety | Null safety en Dart 3, ?, !, ??, late |
| 07 | Clases y OOP | Clases, constructores, herencia, mixins, interfaces |
| 08 | Enums y Records | Enums mejorados (Dart 3), Records, pattern matching |
| 09 | Manejo de errores | try/catch/finally, excepciones personalizadas |
| 10 | Programación asíncrona | Future, async/await, Stream, Completer |
| 11 | Dart avanzado | Extensions, generics, typedefs, bibliotecas |

### 🟡 Nivel Medio — Flutter UI (Módulos 12–19)

| Módulo | Tema | Descripción |
|--------|------|-------------|
| 12 | Widgets básicos | Text, Container, Row, Column, Stack, Image |
| 13 | Layouts | Scaffold, AppBar, Drawer, BottomNav, ListView |
| 14 | Formularios | TextField, Form, validaciones, teclado |
| 15 | Navegación | Navigator, rutas nombradas, go_router |
| 16 | Estado local | setState, StatefulWidget, ciclo de vida |
| 17 | Estado global | Provider, Riverpod — intro y comparativa |
| 18 | Animaciones | AnimationController, Tween, Hero, implícitas |
| 19 | Temas y estilos | ThemeData, dark mode, tipografías, colores |

### 🔴 Nivel Avanzado — Arquitectura y Profesional (Módulos 20–29)

| Módulo | Tema | Descripción |
|--------|------|-------------|
| 20 | Clean Architecture | Capas: presentation, domain, data, core |
| 21 | Riverpod avanzado | AsyncNotifier, Family, AutoDispose, DI |
| 22 | Base de datos local | SQLite con sqflite, Drift, Isar |
| 23 | HTTP y APIs REST | dio, http, modelos, serialización, errores |
| 24 | Internacionalización | l10n, ARB, soporte ES/EN, plurales, fechas |
| 25 | Testing | Unit tests, widget tests, integration tests |
| 26 | Performance | Profiling, repaint boundaries, const, lazy loading |
| 27 | Publicación | Build APK/AAB, firma, Play Store, App Store |
| 28 | Firebase | Auth, Firestore, Storage, Crashlytics |
| 29 | Proyecto final | App completa con arquitectura profesional |

---

## 💡 Consejos para aprender bien

1. **No copies y pegues** — Escribe el código tú mismo. La memoria muscular importa.
2. **Experimenta** — Cada archivo termina con sugerencias de qué modificar. Hazlo.
3. **Rompe las cosas** — Cambia valores, borra líneas, ve qué pasa. Aprender de los errores es real.
4. **Un módulo por día** es suficiente. La consistencia gana a la velocidad.
5. **Usa el debugger** — Aprende a usar los breakpoints desde el principio.
6. **Lee la documentación oficial** — https://dart.dev/guides y https://docs.flutter.dev/
7. **No saltes al módulo de Flutter** sin dominar Dart. Las bases importan.

---

## ⚠️ Errores comunes del principiante

- Querer aprender widgets sin dominar variables, funciones y colecciones.
- Copiar interfaces sin entender el árbol de widgets.
- No observar cuándo una app se reconstruye.
- Confundir estado temporal con datos persistentes.
- Aprender pantallas sin entender arquitectura.

---

## 📖 Dataset: La Biblia RV60

Este repositorio usa la **Biblia Reina-Valera 1960** como dataset de práctica,
en formato SQLite. Es el mismo dataset del Curso de Python.

La base de datos está en `datos/biblia_rv60.sqlite3`. Consulta
`datos/README.md` para la estructura de tablas.

Usaremos este dataset a partir del Módulo 22 (SQLite con Flutter).

---

## 🤝 Cómo apoyar este proyecto

Si este libro te está sirviendo, hay varias formas de apoyarlo y ayudar a
que más personas puedan aprender:

- ⭐ **Dale estrella en GitHub** — ayuda a que otros lo encuentren:
https://github.com/yetsin7/Curso-de-Flutter
- 📣 **Comparte el repositorio** con amigos, compañeros de clase, profesores,
  grupos de estudio, comunidades de programadores en Nicaragua y la región.
- 🐛 **Abre un issue** si encuentras un error, una explicación poco clara,
  un texto mal traducido o algo que se pueda mejorar.
- 🔧 **Manda un pull request** con mejoras: ejemplos nuevos, correcciones,
  ejercicios extra o aclaraciones. Toda contribución es bienvenida.
- 💬 **Cuenta tu experiencia** — si terminaste un módulo, hiciste tu primera
  app o conseguiste tu primer trabajo gracias al libro, compártelo. Motiva
  a otros estudiantes.

Mientras más personas usen y mejoren este recurso, mejor será para los
próximos estudiantes que lleguen.

---

## 📄 Licencia

Este repositorio es de uso libre. Úsalo, modifícalo, compártelo.

No se requiere atribución, aunque siempre se agradece.

---

*Hecho desde Nicaragua 🇳🇮 con dedicación para la comunidad
hispanohablante de Flutter.*
