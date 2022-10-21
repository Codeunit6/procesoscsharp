# Procesos
## Datos personales 
NOMBRE:Fernando Brayan Mejía Gómez 

Grupo: 2722IS

## Copiar repositorio :space_invader:

Recuerda copiar el codigo del proyecto con:
```
git clone
```
### Contribucion al proyecto :globe_with_meridians:
A traves de la contribuicon puedes aplicar codigos con  	:hammer_and_wrench: `gitbash` como lo son:

```
git status
git add .
git commit -m "mesaje"
git push
```
## Codigo
El codigo esta orientado a objetos por lo que su manejo debe ser el debido con respecto a la clase de Procesos. Como se muestra a continuacion
```
public long Prioridad { get; set; }
public string Nombre { get; set; }
```
Asi como tambien el hilo main donde se ejecuta todo el programa
```
 List<Proceso> procesos = new List<Proceso>();
menu(procesos);
```
Todo esta basado mediante una lista de objetos listos para su abstraccion 
La funcion que gira al torno del programa es el menu
```
 //Titulo de programa
            Console.WriteLine("*******************************************");
            Console.WriteLine("*            Programa 2 procesos          *");
            Console.WriteLine("*******************************************");
            Console.WriteLine("*                    Menu                 *");
            Console.WriteLine("* 1. Con parametros definidos             *");
            Console.WriteLine("* 2. Con parametros personalizados        *");
            Console.WriteLine("* 3. Salir                                *");
            Console.WriteLine("*******************************************");
            int opcion = int.Parse(Console.ReadLine());
            switch (opcion)
            {
                case 1:
                    //Llenar informacion
                    llenar(procesos, opcion);
                    //Funcion de ordenar
                    ordenar(procesos);
                    //Funcion para procesos
                    ejecutar(procesos);
                break;
                
                case 2:
                    //Llenar informacion
                    llenar(procesos, opcion);
                    //Funcion de ordenar
                    ordenar(procesos);
                    //Funcion para procesos
                    ejecutar(procesos);
                    break;

                case 3:
                    Environment.Exit(1);
                    break;

                default:
                    Console.WriteLine("Opcion no valida porfavor intente de nuevo");
                    Console.ReadLine();
                    Console.Clear();
                    menu(procesos);
                    break;
            }
```
Todas las funciones reciben parametros para su funcionamiento y tener un control absoluto del codigo
```
public static void llenar(List<Proceso> procesos, int opcion)
```
## Contacto

Si hay alguna dificultad o necesitas alguna ayuda con el proyecto por favor contactame aqui:
- :telephone_receiver:  5540124899

- :envelope:  fernando.brayan.m.g@gmail.com

## Recuerda dar las gracias :blue_heart:

Este proyecto puedes ocuparlo siempre y cuando:
- Da la gracias de manera publica :heartpulse:
- No lo ocupes con fines maliciosos :lock_with_ink_pen:
- Me invites un cafe :coffee:

Este ultimo no es obligatorio.

## Recuerda seguirme en YOUTUBE

![Codeunit06](https://github.com/Codeunit6/Codeunit6/blob/main/anbu.jpg "Codeunit06")

spek14programacion :link: `<link>` : <https://www.youtube.com/channel/UCwPxnD_fdRJggn5ZILh1PRg>

📌 Tengo un canal en youtube donde pudes ver mis tutoriales. 📌

- Puedes ver tutoriales orientados al backend
- Tengo tutoriales de conceptos
- Sigueme si gustas 

## Recuerda darme un follow :black_nib:

En mi perfil podras encontrar cosas interesantes: 

[GitHub](https://github.com/Codeunit6 "GitHub")
