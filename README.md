# Informe Laboratorio Nro 1- Herramienta Github
    Integrantes: Quilumbaquín Lenin
                 Robalino Johanna
                 Jiménez Iván
                 Vallejo Keily
                 Mosquera William 
    NRC: 3725
    Carrera: Electrónica y Automatización
    Asignatura: Programación Orientada a Objetos 
    Docente: Ing. Cesar Osorio
    Tema: Control de Versiones
**OBJETIVOS.-**

      1.-Trabajar de manera colaborativa en proyectos dentro de la herramienta Github como repositorio virtual.
      2.-Analizar la herramienta Github que ayuda a los desarrolladores a almacenar y administrar su código al 
         igual que llevar un control y registro de cualquier cambio realizado con el fin de trabajar y interactuar 
         en conjunto con desarrolladores de otros códigos que estén inscritas en este sitio web.
      3.-Realizar un programa con funciones que valide un número ingresado el cual debe estar en un rango 
         establecido (10 -20), el cual se lo subirá en el repositorio del Docente para evidenciar la 
         implementación y funcionalidad que tiene Git y Github para comprender el manejo de esta herramienta. 
**MARCO TEÓRICO.-**
    
   ### ¿Qué es GIT ?
      El aplicativo Git es un sistema de control de versiones el cual nos va a servir para poder controlar todos 
      los cambios que se han hecho en dicha aplicación y en el código  es decir que se tiene un control absoluto 
      de todo lo que pasa en el código.
      
     Características importantes del Git.
     
   - Rapidez en la gestión de ramas y gestión distribuida es decir que los cambios se importan como ramas 
     adicionales y pueden ser fusionadas de la misma manera como se hace en la rama local.
   - Proporcionar un listado de archivos llamados ¨Commits¨ con la fecha en que ha modificado un archivo.
   - Permite poder restablecer los cambios que se han realizado es decir que puede volver atrás en el tiempo.
      
  ### GITHUB 
     
   - Github es como una red social para programadores; guarda proyectos y cada modificación de las versiones 
     del mismo.
   - Permite integrar colaboradores, revisar sus aporte y fusionarlos en la versiòn final.  
   - Recupera versiones de manera precisa y la identificación de errores se vuelve fácil.
  
     Código implementado en el repositorio remoto del Docente. 
     
            int validar(int &n){
              do{
              cout<<"Ingrese un numero que desee entre 10 y 20: ";
              cin >> n;
              if(n>=10 && n<=20) {
                  cout<<"Numero valido \n";

              }
              else{
              cout<<"Numero no valido! \n";
              system("PAUSE");
              system("cls");
              }
              }while ((n<10)||(n>20));
                  return(n);
             }
#### Capturas de pantalla del proceso realizado con Git y Github

    1.- Creación de la carpeta en el escritorio añadiendo a Git.
   <img src="imagenes/1.png" width=400>
   
    2.- Clonar el repositorio remoto del Docente y creación de la rama Grupo_6
   <img src="imagenes/2.png" width=400>
   
    3.- Añadir los cambios realizados en la rama Grupo_6  del repositorio remoto del Docente 
   <img src="imagenes/3.png" width=400>
    
    4.- Pull requests enviada al Docente.
   <img src="imagenes/4.png" width=400>
        

**CONCLUSIONES.-**

   - Git junto a GitHub  son herramientas   realmente  útiles  a  la  hora  de compartir con otras personas un proyecto por 
     la razón más evidente que es la de  obtener  ayuda para  mejorar el código que uno crea o a su vez para realizar trabajos 
     colaborativos en este caso de estudiantes de la Universidad de las Fuerzas Armadas ¨ESPE¨.
      
   - Como conclusión se puede decir que esta herramienta es muy útil para poder trabajar en conjunto ya que esta creada para 
     que los desarrolladores suban el código de sus aplicaciones y herramientas, y como usuario no solo  tener la facilidad de 
     descargarte o clonar, si no también entrar a perfiles para poder colaborar con el desarrollo del código.
      
   - Podemos concluir que este taller fue de mucha ayuda ya que se obtuvo nuevos conocimientos sobre la herramienta Git Bash 
     y GitHub ya que las mismas son herramientas multifuncionales que nos ayudan a verificar las modificaciones de un archivo 
     que se esté realizando en tiempo real y facilita subir archivos a un repositorio que en este caso el repositorio GitHub.

**RECOMENDACIONES.-**

   - Para hacer un buen uso de las herramientas Git junto con GitHub es importante tener el conocimiento de cada uno de los 
     comandos necesarios para subir, cargar, desarrollar, entre otras funciones que ofrecen las herramientas con las cuales 
     se puede dar un avance en el progreso del trabajo colaborativo entre usuarios. 
   - Es necesario que cada uno de los usuarios que vayan a editar alguna parte del archivo actualice y agregue esos cambios, 
     así como también, es importante que el uso de la herramienta Git junto con GitHub se realice de manera ordenada y 
     correcta para así ver las ventajas y la eficiencia que tienen estas herramientas, ya que de lo contrario, puede existir 
     algún problema en el archivo final.


**Referencias**

     Git vs Github: ¿Cuál es la Diferencia y cómo Empezar?. (2020). De kinsta website: 
     https://kinsta.com/es/base-de-conocimiento/git-vs-github/

     Montiel, O.(2021). La guía para principiantes de Git y Github. De freeCodeCamp:
     https://www.freecodecamp.org/espanol/news/guia-para-principiantes-untitled/


             
