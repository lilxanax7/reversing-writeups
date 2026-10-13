# Reversing writeups

Writeups de ejercicios de ingeniería inversa que voy resolviendo mientras aprendo. Cada uno documenta el proceso completo: reconocimiento, análisis del desensamblado, reconstrucción en pseudocódigo y solución.

## Índice

| # | Ejercicio | Plataforma | Herramientas | Nivel | Temas |
|---|---|---|---|---|---|
| 01a | [Crackme básico](01a-crackme-basico/README.md) | Windows x86-64 (PE32+) | IDA Free | Principiante | Strings y xrefs, `atoi`, comparación contra constante |

## Estructura

Cada ejercicio vive en su propia carpeta, con el writeup en `README.md` y las capturas en `img/`:

```
01a-crackme-basico/
├── README.md
└── img/
```

## Sobre los binarios

Los ejecutables analizados no se incluyen en el repositorio porque son material de terceros. En cada writeup figura el SHA-256 del binario para poder identificarlo.

## Aviso

Contenido con fines exclusivamente educativos. Todos los binarios analizados son ejercicios creados para practicar ingeniería inversa.

## Licencia

Los writeups de este repositorio se publican bajo la licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
