# II_Actividad1

**Owner**: Laura Ramallo Pérez  
**Email**: alu0101246949@ull.edu.es

## Índice
- [II\_Actividad1](#ii_actividad1)
  - [Índice](#índice)
  - [Descripción](#descripción)
  - [Instrucciones](#instrucciones)
    - [Incluir objetos 3D básicos](#incluir-objetos-3d-básicos)
    - [Incluir en el proyecto el paquete "Starter Assets"](#incluir-en-el-proyecto-el-paquete-starter-assets)
    - [Crear un terreno](#crear-un-terreno)
    - [Asignar una etiqueta a cada objeto](#asignar-una-etiqueta-a-cada-objeto)
    - [Utilizar prefabs](#utilizar-prefabs)
    - [Agregar un script](#agregar-un-script)

## Descripción

Práctica 1 - Introducción a Unity  
**Asignatura**: Interfaces Inteligentes

## Instrucciones

### Incluir objetos 3D básicos

He optado por añadir un cubo como en clase:
- GameObject
- 3D Object
- Cubo

### Incluir en el proyecto el paquete "Starter Assets"

He buscado en la Asset Store el paquete Starter Assets - Third Person Character Controller. En Unity:
- Window
- Package Manager
- My assets
- Busco Starter Assets - Third Person Character Controller y lo descargo

![image](C:\Users\lrama\OneDrive\Escritorio\Captura Unity\Consola.png)

### Crear un terreno

- GameObject
- 3D Object
- Terrain

Aplicó una textura al terreno utilizando una imagen proporcionada por el paquete de montañas.

![image](URL_DE_IMAGEN)

### Asignar una etiqueta a cada objeto

Desde el menú de jerarquía del proyecto, he ido seleccionando uno a uno y añadiéndoles un Tag.

![image](URL_DE_IMAGEN)
![image](URL_DE_IMAGEN)

### Utilizar prefabs

He añadido el objeto Box_350x250x200_Prefab a los ya existentes.

![image](URL_DE_IMAGEN)

### Agregar un script

Para ello:
- Assets
- Create
- C# Script

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NewBehaviourScript : MonoBehaviour
{
    public string nombre;

    void Start()
    {
        
    }

    void Update()
    {
        Debug.Log("Nombre del objeto: " + nombre);
    }
}
