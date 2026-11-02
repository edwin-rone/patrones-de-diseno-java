# Patrones de diseño en Java

Implementaciones de patrones de diseño del catálogo GoF, cada uno con su diagrama de clases. Proyecto del curso de Modelado y Programación (Facultad de Ciencias, UNAM).

| Patrón | Tipo | Ejemplo implementado | Clase principal |
| --- | --- | --- | --- |
| [Adapter](adapter) | Estructural | `AdapterPodRacer` hace que una clase con otra interfaz (`PodRacer`) funcione como `Nave` | `CheemsFuerzaEspacial` |
| [Composite](composite) | Estructural | Cajas (`Caja`) que contienen productos u otras cajas, tratadas igual mediante la interfaz `Articulo` | `CheemsMomazon` |
| [Decorator](decorator) | Estructural | Pociones (`PowerUp`) que agregan atributos a un `Personaje` en tiempo de ejecución, apilándose | `JuegoCheems` |
| [Iterator](iterator) | De comportamiento | Recorrer grupos de doctores y pacientes con un mismo `Iterador`, sin exponer cómo se guardan | `CheemsRecepcionista` |

## Cómo ejecutarlos

Cada carpeta es independiente:

```bash
cd decorator
javac *.java
java JuegoCheems
```

## Autor

Edwin Rodríguez Nevárez · edrodnev@gmail.com
