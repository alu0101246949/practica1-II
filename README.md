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
    - [Incluir un objeto de la Asset Store que no sea de los "Starter Assets"](#incluir-un-objeto-de-la-asset-store-que-no-sea-de-los-starter-assets)
    - [Agregar un script](#agregar-un-script)
    - [Gif funcionamiento](#gif-funcionamiento)

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

### Incluir un objeto de la Asset Store que no sea de los "Starter Assets"
![Palmera](https://github.com/alu0101246949/practica1-II/assets/114754476/c63d0b6c-c060-418c-9920-eee7ad62e438)


### Crear un terreno

- GameObject
- 3D Object
- Terrain

Aplicó una textura al terreno utilizando una imagen proporcionada por el paquete de montañas.

![Terreno](https://github.com/alu0101246949/practica1-II/assets/114754476/491a0d46-40dc-44f6-8192-aa3eb9230b78)


### Asignar una etiqueta a cada objeto

A través del menú de jerarquía del proyecto, asigné un Tag a cada elemento de forma individual.

![Tag Cubo](https://github.com/alu0101246949/practica1-II/assets/114754476/0c29c389-ab83-4100-9c8f-249dd4e7e5d8)

![Tag Cubo 2](https://github.com/alu0101246949/practica1-II/assets/114754476/3451e33e-9113-444b-b16a-be8a5af6b320)

### Agregar un script

Para ello:
- Assets
- Create
- C# Script

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class ShowName : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        Debug.Log("My name is " + this.name);
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
![Consola](https://github.com/alu0101246949/practica1-II/assets/114754476/1bc591cd-e9ba-46fb-9729-c20a962fcb0a)
```
### Gif funcionamiento

![GIF](https://github.com/alu0101246949/practica1-II/assets/114754476/0904fb00-e635-4baf-8dcc-be102afa5150)


