# PRACTICAS REPASO
 - Instalar Net Core.
 - Instalar un Editor de Codigo (Visual Studio Code, Visual studio 2022).
 - Crear un proyecto consola en net core.

---
---

# MODULO1: C# Net Core 6 - Desde Cero (con GitHub) 
## Introduccion: 
1. **.NET Framework**:
2. **.NET Core**:

## Primer proyecto
### **Requerimientos**

### **Aplicacion de Consola** Para crear un proyecto de consola en .NET Core 6, puedes seguir estos pasos:

- **Paso 1: Instala .NET Core 6**
- **Paso 2: Abre una Terminal o un Símbolo del Sistema**
- **Paso 3: Crea un Nuevo Proyecto de Consola**
- **Paso 4: Navega al Directorio del Proyecto**
- **Paso 5: Ejecuta la Aplicación de Consola**
- **Paso 6: Edita y Personaliza tu Proyecto**

## Estructuras de Control
- **If**
- **Switch**
- **For**
- **While**
- **Do While**

### Menu de opciones Aplicacion de Consola

## Orientación a Objetos
1. **Clases y Objetos**
2. **Instanciación de Objetos**
3. **Encapsulamiento**
4. **Herencia**
5. **Polimorfismo**
6. **Abstracción**

### Diseño de Aplicaciones de Consola
1. **Aplicación de Consola Interactiva**:
2. **Procesador de Datos en Línea de Comandos**:
3. **Herramienta de Línea de Comandos**:
4. **Demonio o Servicio de Consola**:
5. **Aplicación de Registro y Monitoreo**:
6. **Aplicación de Prueba y Depuración**:
7. **Aplicación de Configuración y Gestión**:

### Librerias clases
1. **Reutilización de Código**
2. **Modularidad**
3. **Separación de Responsabilidades**
4. **Versionamiento**
5. **Referenciación**
6. **Documentación**
7. **Testing**

**Para crear una biblioteca de clases en Visual Studio:**

### Diseño de Aplicaciones Windows (Windows Forms)

---
---
# MODULO2: C# .Net Core - Avanzado  (con GitHub)
1. **Introducción a las APIs REST**:
2. **Entorno de Desarrollo**:
3. **Fundamentos de C#**:
4. **ASP.NET Core**:
5. **Routing en ASP.NET Core**:
6. **Modelos de Datos**:
7. **Controladores y Acciones**:
8. **Métodos HTTP**:
9. **Serialización y Deserialización JSON**:
10. **Autenticación y Autorización**:
11. **Versionado de la API**:
12. **Documentación de la API**:
13. **Manejo de Errores**:
14. **Seguridad**:
15. **Buenas Prácticas de Desarrollo**:
16. **Gestion de Paquetes con Nuget**
17. **Conexion a Base de datos ADO.NET**
18. **Bases de datos con Entity Framework**
19. **Aplicaciones Web**
---
---
# MISCELANEOS
### Commando Dotnet
### Commando GitHub
---
---
***
# Recursos
 - https://github.com/vachocalla/CourseM1CSharp
 - https://code.visualstudio.com/download
 - https://visualstudio.microsoft.com/es/vs/community/
 - https://git-scm.com/downloads

# C# Net Core 6 - Desde Cero (con GitHub) 
## Introduccion: 
La diferencia principal entre ".NET Framework" y ".NET Core" se refiere a su diseño, propósito y compatibilidad. Aquí tienes una descripción de ambas:

1. **.NET Framework**:

   - Es un framework de desarrollo de software desarrollado por Microsoft que ha estado disponible durante varias décadas y se ha utilizado principalmente en sistemas operativos Windows.
   - Fue diseñado inicialmente como un framework para aplicaciones Windows y de escritorio, y posteriormente se amplió para admitir aplicaciones web a través de ASP.NET.
   - Está diseñado para ser una plataforma integral para el desarrollo de aplicaciones Windows, incluyendo aplicaciones de escritorio (Windows Forms y WPF), servicios de Windows, aplicaciones web ASP.NET, y más.
   - Está vinculado al sistema operativo Windows y se distribuye como parte del sistema operativo o como una descarga independiente.

2. **.NET Core**:

   - Es una plataforma de desarrollo de software de código abierto y multiplataforma también desarrollada por Microsoft.
   - Fue diseñado para ser más liviano y modular en comparación con .NET Framework. Esto significa que puedes elegir componentes específicos y dependencias para incluir en tu aplicación, lo que la hace más eficiente y adecuada para escenarios como contenedores y aplicaciones web modernas.
   - Es completamente multiplataforma y se ejecuta en Windows, Linux y macOS. Esto lo hace ideal para desarrollar aplicaciones en una variedad de sistemas operativos.
   - A partir de .NET Core 3.0, Microsoft unificó las plataformas .NET Framework y .NET Core bajo el nombre ".NET", lo que significa que .NET Core se convirtió en la base de la nueva plataforma .NET. 

## Primer proyecto

### **Requerimientos**
- Instalar: 
    - https://dotnet.microsoft.com/es-es/download/dotnet/6.0 (Recomendado)
    - https://dotnet.microsoft.com/es-es/download/dotnet/7.0 
    - https://dotnet.microsoft.com/es-es/download/dotnet/8.0 (Recomendado)

### **Aplicacion de Consola** Para crear un proyecto de consola en .NET Core 6, puedes seguir estos pasos:

- **Paso 1: Instala .NET Core 6**

    Asegúrate de tener instalado .NET Core 6 en tu máquina. Puedes descargarlo desde el sitio web oficial de .NET: https://dotnet.microsoft.com/download/dotnet/6.0

- **Paso 2: Abre una Terminal o un Símbolo del Sistema**

    Abre una terminal o un símbolo del sistema en tu sistema operativo. Esto es donde ejecutarás los comandos de .NET Core para crear y ejecutar tu proyecto de consola.

- **Paso 3: Crea un Nuevo Proyecto de Consola**

    Ejecuta el siguiente comando para crear un nuevo proyecto de consola en .NET Core 6. Reemplaza `"MiProyectoConsola"` con el nombre que desees para tu proyecto:

    ```bash
    dotnet --list-sdks

    dotnet new console -n MiProyectoConsola

    dotnet new console -n <nombre_del_proyecto> --framework net6.0
    ```

    Este comando crea un nuevo proyecto de consola llamado "MiProyectoConsola".

- **Paso 4: Navega al Directorio del Proyecto**

    Utiliza el comando `cd` para cambiar al directorio del proyecto que acabas de crear:

    ```bash
    cd MiProyectoConsola
    ```

- **Paso 5: Ejecuta la Aplicación de Consola**

    Una vez que estés dentro del directorio de tu proyecto, puedes compilar y ejecutar la aplicación de consola utilizando el siguiente comando:

    ```bash
    dotnet run
    ```

    Esto compilará y ejecutará tu aplicación de consola. Verás la salida en la terminal.

- **Paso 6: Edita y Personaliza tu Proyecto**

    Ahora puedes abrir el proyecto en tu editor de código favorito (como Visual Studio Code o Visual Studio) y comenzar a editar y personalizar tu aplicación de consola en C# según tus necesidades.

    El archivo principal de la aplicación de consola es `Program.cs`, y es donde encontrarás el método `Main`, que es el punto de entrada de tu programa.

## Estructuras de Control
- **If**
    ```csharp
    public static void EjemploIf()
    {
        int edad = 25;

        if (edad >= 18)
        {
            Console.WriteLine("Eres mayor de edad.");
        }
        else
        {
            Console.WriteLine("Eres menor de edad.");
        }
    }
    ```

- **Switch**
    ```csharp
    public static void EjemploSwitch()
    {
        int diaSemana = 3;
        string nombreDia;

        switch (diaSemana)
        {
            case 1:
                nombreDia = "Lunes";
                break;
            case 2:
                nombreDia = "Martes";
                break;
            case 3:
                nombreDia = "Miércoles";
                break;
            default:
                nombreDia = "Día no válido";
                break;
        }

        Console.WriteLine($"Hoy es {nombreDia}.");
    }
    ```

- **For**
    ```csharp
    public static void EjemploFor()
    {
        for (int i = 1; i <= 5; i++)
        {
            Console.WriteLine($"Iteración {i}");
        }
    }
    ```

- **While**
    ```csharp
    public static void EjemploWhile()
    {
        int contador = 0;

        while (contador < 5)
        {
            Console.WriteLine($"Contador: {contador}");
            contador++;
        }
    }
    ```

- **Do While**
    ```csharp
    public static void EjemploDoWhile()
    {
        int contador = 0;

        do
        {
            Console.WriteLine($"Contador: {contador}");
            contador++;
        } while (contador < 5);
    }
    ```

### Menu de opciones
Usando los anteriores metodos crear un menu para invocar a cada unos de los metodos creados.

Ejemplo Completo en URL: 

```csharp
using System;

public class Program
{
    public static void Main(string[] args)
    {
        while (true)
        {
            Console.WriteLine("Seleccione una opción:");
            Console.WriteLine("1. Ejemplo de if");
            Console.WriteLine("2. Ejemplo de switch");
            Console.WriteLine("3. Ejemplo de for");
            Console.WriteLine("4. Ejemplo de while");
            Console.WriteLine("5. Ejemplo de do-while");
            Console.WriteLine("0. Salir");

            int opcion;
            if (int.TryParse(Console.ReadLine(), out opcion))
            {
                switch (opcion)
                {
                    case 1:
                        EjemploIf();
                        break;
                    case 2:
                        EjemploSwitch();
                        break;
                    case 3:
                        EjemploFor();
                        break;
                    case 4:
                        EjemploWhile();
                        break;
                    case 5:
                        EjemploDoWhile();
                        break;
                    case 0:
                        return; // Salir del programa
                    default:
                        Console.WriteLine("Opción no válida. Inténtelo de nuevo.");
                        break;
                }
            }
            else
            {
                Console.WriteLine("Opción no válida. Inténtelo de nuevo.");
            }
        }
    }
}
```

### Clases y Objetos
La programación orientada a objetos (POO) es un paradigma de programación fundamental en C# y .NET Core 6. En la POO, los programas se organizan en objetos que representan entidades del mundo real y las interacciones entre ellos.

1. **Clases y Objetos**:
   - Una clase es una plantilla o un plano para crear objetos. Define los atributos (propiedades) y los métodos (funciones) que los objetos de esa clase tendrán.
   - Un objeto es una instancia de una clase, es decir, una entidad concreta creada a partir de una clase.

   ```csharp
   // Definición de una clase
   public class Persona
   {
       // Atributos (propiedades)
       public string Nombre { get; set; }
       public int Edad { get; set; }

       // Método
       public void Saludar()
       {
           Console.WriteLine($"Hola, soy {Nombre} y tengo {Edad} años.");
       }
   }

   // Creación de un objeto
   Persona persona1 = new Persona();
   persona1.Nombre = "Juan";
   persona1.Edad = 30;
   persona1.Saludar(); // Llamada a un método
   ```
2. **Instanciación de Objetos**:
   - Los objetos se crean utilizando el operador `new`.
   - Los objetos pueden ser destruidos automáticamente por el recolector de basura de .NET cuando ya no son accesibles.

   ```csharp
   Persona persona = new Persona();
   ```

3. **Encapsulamiento**:
   - El encapsulamiento es el principio de POO que implica ocultar los detalles internos de una clase y exponer solo las interfaces necesarias.
   - En C#, se utilizan modificadores de acceso como `public`, `private`, `protected`, etc., para controlar la visibilidad de atributos y métodos.

   ```csharp
   public class CuentaBancaria
   {
       private decimal saldo;

       public decimal Saldo
       {
           get { return saldo; }
           private set { saldo = value; }
       }

       public void Depositar(decimal cantidad)
       {
           saldo += cantidad;
       }

       public void Retirar(decimal cantidad)
       {
           if (cantidad <= saldo)
               saldo -= cantidad;
           else
               Console.WriteLine("Saldo insuficiente.");
       }
   }
   ```

4. **Herencia**:
   - La herencia permite que una clase (subclase o derivada) herede atributos y métodos de otra clase (superclase o base).
   - C# admite la herencia única, lo que significa que una clase solo puede heredar de una sola clase base.

   ```csharp
   public class Empleado : Persona
   {
       public decimal Salario { get; set; }
   }
   ```

5. **Polimorfismo**:
   - El polimorfismo permite que objetos de diferentes clases respondan de manera diferente a la misma llamada de método.
   - Se puede lograr mediante la sobrecarga de métodos y la implementación de interfaces.

   ```csharp
   public interface IVehiculo
   {
       void Arrancar();
   }

   public class Coche : IVehiculo
   {
       public void Arrancar()
       {
           Console.WriteLine("El coche arrancó.");
       }
   }

   public class Moto : IVehiculo
   {
       public void Arrancar()
       {
           Console.WriteLine("La moto arrancó.");
       }
   }
   ```

6. **Abstracción**:
   - La abstracción consiste en representar los aspectos esenciales de un objeto mientras se ocultan los detalles no esenciales.
   - Se logra mediante la creación de clases abstractas e interfaces.

   ```csharp
   public abstract class Forma
   {
       public abstract double CalcularArea();
   }
   ```

### Diseño de Aplicaciones de Consola
En C# con .NET Core, puedes crear diferentes tipos de aplicaciones de consola según tus necesidades y requisitos específicos. Aquí hay algunos tipos comunes de aplicaciones de consola que puedes desarrollar:

1. **Aplicación de Consola Interactiva**:
   - Este tipo de aplicación permite la interacción continua con el usuario a través de la consola.
   - Puedes crear menús, solicitar entrada del usuario y proporcionar respuestas en tiempo real.

2. **Procesador de Datos en Línea de Comandos**:
   - Estas aplicaciones procesan datos desde la línea de comandos o mediante argumentos de línea de comandos.
   - Son útiles para tareas automatizadas y procesamiento por lotes.
   - Ejemplo: Un convertidor de archivos por lotes, un programa para descargar archivos desde la web mediante URL, etc.

3. **Herramienta de Línea de Comandos**:
   - Estas aplicaciones proporcionan una interfaz de línea de comandos para realizar tareas específicas.
   - Pueden aceptar comandos y argumentos para realizar funciones específicas.
   - Ejemplo: Herramientas de línea de comandos para compilar código, administrar paquetes, generar documentación, etc.

4. **Demonio o Servicio de Consola**:
   - Estas aplicaciones se ejecutan en segundo plano como demonios o servicios de Windows.
   - Suelen ejecutarse sin interacción del usuario y pueden realizar tareas programadas o servicios continuos.
   - Ejemplo: Un servidor de chat, un servicio de monitoreo de archivos, un demonio de respaldo automático, etc.

5. **Aplicación de Registro y Monitoreo**:
   - Estas aplicaciones recopilan y registran datos, estadísticas o eventos en la consola.
   - Pueden ser útiles para el monitoreo en tiempo real o el registro de información importante.
   - Ejemplo: Un servidor de registro de eventos, una aplicación de monitoreo de recursos del sistema, etc.

6. **Aplicación de Prueba y Depuración**:
   - Estas aplicaciones se utilizan para probar y depurar código y lógica de aplicaciones.
   - Pueden proporcionar resultados de pruebas y ayudar en la depuración de errores.
   - Ejemplo: Una aplicación de pruebas unitarias de consola, una utilidad de depuración de código, etc.

7. **Aplicación de Configuración y Gestión**:
   - Estas aplicaciones permiten configurar y gestionar aspectos de un sistema o aplicación.
   - Se utilizan para configurar parámetros, opciones y ajustes.
   - Ejemplo: Una aplicación para configurar opciones de red, una utilidad de configuración de base de datos, etc.

### Librerias clases
En C#, una biblioteca de clases (Class Library en inglés) es un proyecto que contiene clases, interfaces, métodos y otros tipos de datos que pueden ser utilizados por otras aplicaciones o proyectos. Las bibliotecas de clases se compilan en ensamblados (.dll) que pueden ser referenciados por otros proyectos en la misma solución o por aplicaciones externas.

1. **Reutilización de Código**: Las bibliotecas de clases permiten la reutilización de código. Puedes crear una biblioteca que contiene clases y funciones comunes que luego pueden ser utilizadas en múltiples proyectos sin necesidad de volver a escribir el código.

2. **Modularidad**: Las bibliotecas de clases ayudan a organizar el código en módulos lógicos y separados. Cada biblioteca puede representar una funcionalidad específica o un conjunto de características relacionadas.

3. **Separación de Responsabilidades**: Al separar el código en bibliotecas de clases, puedes seguir el principio de Responsabilidad Única (SRP), que establece que una clase debe tener una única razón para cambiar.

4. **Versionamiento**: Las bibliotecas de clases se pueden versionar, lo que facilita la actualización de las bibliotecas sin afectar el código de las aplicaciones que las utilizan. Esto es importante para el mantenimiento a largo plazo.

5. **Referenciación**: Para utilizar una biblioteca de clases en un proyecto, debes agregar una referencia a la biblioteca en el proyecto. Esto permite que el proyecto acceda a las clases y funciones proporcionadas por la biblioteca.

6. **Documentación**: Es importante proporcionar documentación clara y detallada para las bibliotecas de clases, para que los desarrolladores que las utilicen comprendan cómo usarlas correctamente.

7. **Testing**: Debes incluir pruebas unitarias para las clases y funciones dentro de una biblioteca de clases para garantizar su correcto funcionamiento y detectar errores.

**Para crear una biblioteca de clases en Visual Studio:**

1. Abre Visual Studio y crea un nuevo proyecto seleccionando la plantilla "Biblioteca de clases (.NET Core)" o "Biblioteca de clases (.NET Framework)" según tus necesidades.

2. Agrega clases y funcionalidades a la biblioteca según los requisitos de tu proyecto.

3. Compila la biblioteca para generar el ensamblado (.dll).

4. Puedes distribuir el ensamblado a otros proyectos o desarrolladores según sea necesario.

Las bibliotecas de clases son una parte fundamental de la arquitectura de software en C# y se utilizan ampliamente para crear componentes reutilizables y fáciles de mantener.

### Diseño de Aplicaciones Windows (Windows Forms)
Aplicacion Practica: Proyecto completo de un Sistema de Ventas.

# MODULO2: C# .Net Core - Avanzado  (con GitHub)
1. **Introducción a las APIs REST**:
   - Qué es una API REST.
   - Principios de diseño de APIs RESTful.
   - HTTP como protocolo de comunicación.

2. **Entorno de Desarrollo**:
   - Configuración de un entorno de desarrollo de C# y .NET.
   - Uso de un IDE como Visual Studio o Visual Studio Code.

3. **Fundamentos de C#**:
   - Manejo de excepciones.

4. **ASP.NET Core**:
   - Introducción a ASP.NET Core.
   - Configuración de proyectos web en ASP.NET Core.
   - Middleware y pipeline de solicitud.

5. **Routing en ASP.NET Core**:
   - Enrutamiento de solicitudes HTTP.
   - Definición de rutas para los recursos de la API.
   - Parámetros en las rutas.

6. **Modelos de Datos**:
   - Creación de modelos de datos para representar recursos.
   - Validación de datos de entrada.

7. **Controladores y Acciones**:
   - Creación de controladores.
   - Definición de acciones para manejar solicitudes HTTP.
   - Retorno de respuestas JSON.

8. **Métodos HTTP**:
   - Uso de métodos HTTP estándar (GET, POST, PUT, DELETE).
   - Manejo de solicitudes y respuestas.

9. **Serialización y Deserialización JSON**:
   - Uso de bibliotecas de serialización JSON como Newtonsoft.Json o System.Text.Json.

10. **Autenticación y Autorización**:
    - Implementación de autenticación y autorización en una API REST.
    - Uso de tokens JWT.

11. **Versionado de la API**:
    - Estrategias para el versionado de la API.
    - Versionado en la ruta o en los encabezados.

12. **Documentación de la API**:
    - Generación de documentación automática con Swagger/OpenAPI.
    - Descripción de endpoints, parámetros y respuestas.

13. **Manejo de Errores**:
    - Manejo adecuado de errores y excepciones en la API.
    - Retorno de códigos de estado y mensajes de error.

14. **Seguridad**:
    - Buenas prácticas de seguridad en APIs REST.
    - Protección contra ataques comunes.

15. **Buenas Prácticas de Desarrollo**:
    - Patrones de diseño.
    - Principios SOLID y DRY.

16. **Gestion de Paquetes con Nuget**
17. **Conexion a Base de datos ADO.NET**
18. **Bases de datos con Entity Framework**
19. **Aplicaciones Web**

---
---
# MISCELANEOS
## Commando Dotnet
.NET CLI (Command-Line Interface) proporciona una serie de comandos esenciales para el desarrollo de aplicaciones en .NET, ya sea para crear, compilar, ejecutar o administrar proyectos y soluciones. A continuación, se presentan algunos de los comandos esenciales de .NET CLI:

1. **dotnet new**: Este comando se utiliza para crear nuevos proyectos y archivos de código fuente a partir de plantillas. Algunos ejemplos incluyen:
   - `dotnet new console`: Crea un proyecto de aplicación de consola.
   - `dotnet new webapi`: Crea un proyecto de API web.
   - `dotnet new classlib`: Crea un proyecto de biblioteca de clases.

2. **dotnet build**: Compila un proyecto o una solución. Por ejemplo:
   - `dotnet build`: Compila el proyecto actual.

3. **dotnet run**: Ejecuta una aplicación. Por ejemplo:
   - `dotnet run`: Ejecuta la aplicación en el proyecto actual.

4. **dotnet publish**: Publica una aplicación para su distribución. Por ejemplo:
   - `dotnet publish -c Release`: Publica la aplicación en modo de lanzamiento.

5. **dotnet test**: Ejecuta pruebas unitarias en un proyecto. Por ejemplo:
   - `dotnet test`: Ejecuta todas las pruebas en el proyecto actual.

6. **dotnet restore**: Restaura las dependencias de un proyecto, descargando los paquetes NuGet necesarios.

7. **dotnet add reference**: Agrega una referencia a un proyecto. Por ejemplo:
   - `dotnet add reference MiProyecto.csproj`: Agrega una referencia al proyecto especificado.

8. **dotnet ef**: Proporciona herramientas de Entity Framework Core para trabajar con bases de datos. Por ejemplo:
   - `dotnet ef migrations add NombreMigracion`: Crea una nueva migración de base de datos.

9. **dotnet pack**: Empaqueta una biblioteca de clases para su distribución como paquete NuGet.

10. **dotnet clean**: Elimina los archivos generados durante la compilación y restaura el proyecto a su estado original.

11. **dotnet --list-sdks**: Lista todas las versiones del SDK de .NET instaladas en tu sistema.

12. **dotnet --list-runtimes**: Lista todas las versiones de .NET Core/.NET instaladas en tu sistema.

13. **dotnet --version**: Muestra la versión actual del SDK de .NET instalada.

14. **dotnet new sln**: Crea una nueva solución (.sln) que puede contener varios proyectos.

15. **dotnet sln add Proyecto.csproj**: Agrega un proyecto a una solución existente.

16. **dotnet sln remove Proyecto.csproj**: Elimina un proyecto de una solución existente.

17. **dotnet sln list**: Lista los proyectos dentro de una solución.

## Commando GitHub
Trabajar con GitHub de manera colaborativa implica la coordinación y el uso de comandos clave para mantener un flujo de trabajo eficiente. Aquí tienes algunos comandos esenciales de Git y GitHub:

1. **Clonar un Repositorio**:
   - `git clone <URL_del_repositorio>`: Clona un repositorio remoto en tu máquina local.

2. **Actualizar el Repositorio Local**:
   - `git pull origin <rama>`: Obtiene las últimas actualizaciones desde el repositorio remoto a tu repositorio local.

3. **Crear una Rama**:
   - `git checkout -b <nombre_de_la_rama>`: Crea y cambia a una nueva rama de desarrollo.

4. **Cambiar de Rama**:
   - `git checkout <nombre_de_la_rama>`: Cambia a una rama existente.

5. **Agregar Cambios Locales**:
   - `git add .`: Agrega todos los cambios locales al área de preparación.
   - `git add <archivo>`: Agrega un archivo específico al área de preparación.

6. **Confirmar Cambios Locales**:
   - `git commit -m "Mensaje del commit"`: Confirma los cambios en tu rama local con un mensaje descriptivo.

7. **Subir Cambios al Repositorio Remoto**:
   - `git push origin <nombre_de_la_rama>`: Sube tus cambios locales a la rama correspondiente en el repositorio remoto.

8. **Ver el Estado del Repositorio**:
   - `git status`: Muestra el estado actual de los archivos en tu repositorio local.

9. **Ver el Historial de Commits**:
   - `git log`: Muestra el historial de commits en la rama actual.

10. **Sincronizar Rama Principal con Cambios Remotos**:
    - `git pull origin main`: Actualiza la rama principal con los cambios remotos antes de crear una nueva rama de desarrollo.

11. **Resolver Conflictos de Fusión**:
    - Cuando se producen conflictos al fusionar ramas, usa un editor de texto para resolver los conflictos y luego confirma los cambios resueltos.

12. **Fusionar Cambios**:
    - `git merge <nombre_de_la_rama>`: Fusiona los cambios de una rama en la rama actual.

13. **Crear y Fusionar Pull Requests**:
    - Utiliza la interfaz de GitHub para crear un pull request desde una rama de desarrollo a la rama principal. Luego, revisa, discute y fusiona los cambios.

14. **Revisar y Comentar Pull Requests**:
    - Los desarrolladores pueden revisar el código y dejar comentarios en los pull requests de otros miembros del equipo.

15. **Eliminar Ramas Obsoletas**:
    - `git branch -d <nombre_de_la_rama>`: Elimina una rama local después de que se haya fusionado.

16. **Configurar el Flujo de Trabajo**:
    - Puedes establecer configuraciones globales como nombre y correo electrónico usando `git config`.