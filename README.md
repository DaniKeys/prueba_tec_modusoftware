### APi rest 
***proyecto_prueba_tec_modusoftwar*** , es una APi REST de consultas  de operaciones matematicas. La logica del proyecto es recorrer una lista de numeros obtenidos por su ID  y hacer operaciones matematicas con un arreglo de numeros primos, operaciones entre ellas
modulos, dependiendo del residuo se almacenan en listas independientes. el ordenamiento varia dependiendo de la cantidad de iteraciones
### Instrucciones de uso

 * Cree la base de datos en su gestor de preferencia , el archivo `script.sql` dado en el empaquetamiento del proyecto
 * Conecte su base de datos a Java
 * antes de consumir la APi levante su Api en el ide para establecer conexion con su cliente o navegador
 * Inserte la siguiente URL en su cliente o navegador reemplaze los valores de `dominio` y `port` por su valores
> http:/dominio:port/app/consulta
 * cree un body en formato JSON donde estipule el id y numero de iteracion
 ~~~
  {
        "id": 1,
        "q":3
   }
 ~~~
 * tenga presente la informacion del endpoint y su nombre de recurso
 `/app/consulta`
 
> en caso de usar **Postman** utilize el verbo HTTP `POST` par su consulta

 ###Tecnologias y componentes
 >STS,MySql,Postman,SpringBoot,SpringDataJPA,Junit,lombok
