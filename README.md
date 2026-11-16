# QUIMERA LABS

Equipos de laboratorio de química en 3D interactivo, parte del **Proyecto QUIMERA** (Química, Innovación, Modelado, Experimentación, Recursos, Aprendizaje).

Desarrollado por **Isai Severiano Felix Sopla** · ACS UNMSM Student Chapter.

El objetivo es que el estudiante conozca el equipo, sepa armarlo y lo haya operado antes de pisar el laboratorio real.

**Sitio:** https://maestrosuprem0.github.io/QUIMERA-LABS/

## Equipos

| # | Equipo | Qué se practica |
|---|---|---|
| 01 | [Titulación ácido-base](https://maestrosuprem0.github.io/QUIMERA-LABS/titulacion/) | Lectura del menisco, viraje de la fenolftaleína con pH calculado, cálculo de la concentración |
| 02 | [Destilación por arrastre de vapor](https://maestrosuprem0.github.io/QUIMERA-LABS/arrastre-vapor/) | Orden agua-calor, ley de Dalton, efecto de la altitud, decantación de aceites que flotan o se hunden |
| 03 | [Extracción Soxhlet](https://maestrosuprem0.github.io/QUIMERA-LABS/soxhlet/) | Ciclos del sifón, errores de montaje, porcentaje de grasa por gravimetría |

Cada equipo tiene tres modos:

1. **Explorar:** girar el modelo y tocar cada pieza para ver su función, su uso y su error común.
2. **Ensamblar:** armar el equipo con la cámara fija; una pieza mal colocada vuelve a su sitio.
3. **Operar:** usar llaves, perillas e interruptores y ver qué pasa.

## Estructura

```
index.html              portada
titulacion/index.html   Equipo 01
arrastre-vapor/index.html  Equipo 02
soxhlet/index.html      Equipo 03
```

Cada equipo es un solo archivo HTML. Los modelos 3D se generan con código (Three.js), sin archivos de modelo externos.

## Tecnología y límites

- [Three.js](https://threejs.org/) 0.160, cargado desde jsDelivr: **necesita conexión a internet**.
- Funciona mejor en computadora; en celular, el modo Ensamblar es incómodo.
- La química de cada modo Operar está explicada en el propio panel. Los tiempos y caudales están simplificados para que una práctica dure minutos.

## Publicación

GitHub Pages, desde la rama `main`, carpeta raíz.
