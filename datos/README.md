# Carpeta `datos/` — Recursos del Curso de Flutter

Esta carpeta contiene la base de datos propia de este curso. La copia local de
`biblia_rv60.sqlite3` se usa en los scripts Dart de consola y puede
personalizarse sin afectar a otros repositorios.

Ruta relativa desde cualquier capítulo de este libro (scripts Dart de consola):

```dart
import 'package:path/path.dart' as path;

final scriptDir = path.dirname(Platform.script.toFilePath());
final dbPath = path.normalize(
  path.join(scriptDir, '..', '..', 'datos', 'biblia_rv60.sqlite3')
);
```

> **Nota sobre proyectos Flutter reales:** Los proyectos Flutter completos
> (como `29-app-biblia-flutter/`) incluyen su propia copia de la base de datos
> en `assets/` porque Flutter accede a los datos como assets del bundle de la app,
> no como archivos del sistema de archivos del host.
