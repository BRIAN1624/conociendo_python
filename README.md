# 🐍 Conociendo a Python — Ejercicios y Concurso

Repositorio de ejercicios progresivos de Python para principiantes, organizado
por temas y pensado como **concurso de programación**: los participantes
resuelven los ejercicios, los entregan vía *Pull Request* y al final del curso
se elige un ganador por categoría.

> 📚 Basado en los artículos de ejercicios de [frexus.dev](https://www.frexus.dev/),
> ampliados con una categoría original de funciones.

---

## 📖 ¿Qué encontrarás aquí?

| Categoría | Ejercicios | Tema |
|-----------|:---:|------|
| [01 — Entrada y salida](ejercicios/01_entrada_y_salida/) | 6 | `print`, `input`, archivos |
| [02 — Estructura de control](ejercicios/02_estructura_de_control/) | 10 | `if`, `elif`, `else` |
| [03 — Estructuras cíclicas](ejercicios/03_estructuras_ciclicas/) | 10 | `for`, `while` |
| [04 — Arreglos](ejercicios/04_arreglos/) | 10 | listas |
| [05 — Funciones](ejercicios/05_funciones/) | 10 | `def`, `return`, parámetros |
| **Total** | **46** | |

Cada categoría incluye un `README.md` con el índice y un archivo `.md` por
ejercicio, con enunciado, ejemplo de entrada/salida y pistas.

---

## 🚀 Cómo participar

### 1. Haz un fork del repositorio

Haz clic en el botón **Fork** (arriba a la derecha) para crear tu propia copia.

### 2. Clona tu fork en local

```bash
git clone https://github.com/<tu-usuario>/python-ejercicios-iniciales.git
cd python-ejercicios-iniciales
```

### 3. Añade el repositorio original como `upstream`

Esto te permitirá sincronizar cambios si el profesor actualiza los enunciados:

```bash
git remote add upstream https://github.com/<profesor>/python-ejercicios-iniciales.git
```

### 4. Crea una rama por categoría

```bash
git checkout -b entrega/01-entrada-salida
```

### 5. Resuelve los ejercicios en tu carpeta personal

Cada alumno entrega dentro de `entregas/<tu-usuario>/<categoria>/`:

```text
entregas/<tu-usuario>/01_entrada_y_salida/
├── ejercicio_01.py
├── ejercicio_02.py
├── ejercicio_03.py
├── ejercicio_04.py
├── ejercicio_05.py
└── ejercicio_06.py
```

> ⚠️ **No modifiques** nada dentro de `ejercicios/` ni las carpetas de otros
> alumnos. Solo escribes dentro de tu propia carpeta en `entregas/`.

### 6. Haz commit y push

```bash
git add entregas/01_entrada_y_salida/<tu-usuario>/
git commit -m "Entrega categoría 01 — <tu-usuario>"
git push origin entrega/01-entrada-salida
```

### 7. Abre un Pull Request

Desde GitHub, abre un PR hacia la rama `main` del repositorio original.
Usa el título: `[01 Entrada/Salida] <tu-usuario>`.

Repite los pasos 4–7 para cada categoría.

📘 **Instrucciones detalladas:** consulta [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## 🏆 Reglas del concurso

- **Un PR por categoría.** No mezcles varias categorías en un solo PR.
- **Solo se evalúa lo que esté dentro de** `entregas/<categoria>/<tu-usuario>/`.
- **No copies soluciones de otros.** Los PR quedan registrados con fecha y autor.
- **Fecha límite:** consulta [`BASES.md`](BASES.md).
- **Criterios de evaluación:** correctitud, claridad del código, uso idiomático
  de Python y creatividad en la solución.
- **Premio por categoría** y **mención al ganador global** al cierre del curso.

📜 **Bases completas:** consulta [`BASES.md`](BASES.md).

---

## 🗂️ Estructura del repositorio

```text
python-ejercicios-iniciales/
├── README.md                    ← este archivo
├── CONTRIBUTING.md              ← cómo entregar (fork → PR)
├── BASES.md                     ← reglas y fechas del concurso
├── .gitignore
│
├── .github/
│   └── pull_request_template.md ← checklist al abrir PR
│
├── ejercicios/                  ← ENUNCIADOS (solo lectura)
│   ├── README.md
│   ├── 01_entrada_y_salida/
│   ├── 02_estructura_de_control/
│   ├── 03_estructuras_ciclicas/
│   ├── 04_arreglos/
│   └── 05_funciones/
│
├── entregas/                    ← SOLUCIONES de los alumnos
│   ├── README.md
│   ├── _plantilla/
│   ├── 01_entrada_y_salida/
│   ├── 02_estructura_de_control/
│   ├── 03_estructuras_ciclicas/
│   ├── 04_arreglos/
│   └── 05_funciones/
│
└── soluciones/                  ← (se crea AL CERRAR el concurso)
    └── <categoria>/ganador_<usuario>/
```

---

## 🧪 Cómo probar tus ejercicios

Desde la carpeta de tu entrega:

```bash
cd entregas/01_entrada_y_salida/<tu-usuario>/
python ejercicio_01.py
```

Si usas Windows y tienes varios Pythons instalados:

```powershell
py ejercicio_01.py
```

**Requisitos:** Python 3.10 o superior. No se necesitan librerías externas
(todo se resuelve con la biblioteca estándar).

---

## ❓ Preguntas frecuentes

**¿Puedo usar IA o buscar en Google?**
Sí, pero el código debe ser tuyo y debes entenderlo. En la revisión se valora
la claridad y que sepas explicar tu solución.

**¿Qué pasa si me equivoco en un ejercicio ya entregado?**
Puedes hacer un nuevo commit en la misma rama; el PR se actualiza solo.

**¿Puedo entregar solo algunas categorías?**
Sí. Cada categoría se evalúa por separado.

**¿Dónde veo los resultados?**
En [`BASES.md`](BASES.md) se publicarán las fechas de cierre y premiación.
Al finalizar, la carpeta `soluciones/` contendrá las mejores entregas de cada
categoría (con permiso de sus autores).

**¿Cómo sincronizo mi fork si el profesor actualiza el repo?**
```bash
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```

---

## 🤝 Contribuir

Este repositorio es material educativo. Si encuentras un error en un enunciado
o quieres proponer un ejercicio nuevo, abre un *issue* describiendo el problema
o la propuesta.

---

## 📜 Licencia

Material educativo de libre uso para fines no comerciales.
Los enunciados originales pertenecen a [frexus.dev](https://www.frexus.dev/);
la organización y los ejercicios de funciones son de elaboración propia.

---

## 🙌 Agradecimientos

A [frexus.dev](https://www.frexus.dev/) por los artículos de ejercicios de
Python que sirven de base a este curso, y a todos los alumnos que participan
en el concurso.
