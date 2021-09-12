 TALLER UNIDAD 1:
 Crea el diagrama de clases siguiente:

a. Diagrama una clase abstracta Empleado con los atributos: documento, nombre, sueldoHora (y otros que creas necesarios) y crea sus correspondientes métodos getteres y setteres, también puedes crear un constructor que tenga todos los atributos para asignar los atributos y un constructor vacio. Crea una clase Desarrollador (sin atributos ni métodos), una clase GestorProyectos con los atributos: área y sus métodos set y get. Crea una clase Admin sin atributos ni métodos. Establece la relación de herencia entre ellos. Y puedes ir realizando el diagrama de clases.
b. Diagrama una clase Empresa con los atributos: nit, nombre, direccion, ciudad (y los creas necesarios); crea sus correspondientes métodos getteres y setteres. Crea una clase EmpresaDesarrollo sin atributos ni métodos y establece su relación de herencia.
c. Establece la relación entre clase Empleado y Empresa. Supongamos que: un empleado solo puede trabajar en una única empresa.

2. Crear las clases Java:
a. Crear las clases anteriormente diagramadas a Clases Java.
b. Crea 3 paquetes en java: Un paquete llamado modelos con las clases: Empleado, Desarrollador, GestorProyectos, Admin, Empresa, EmpresaDesarrollo. Un paquete llamado operaciones, y crear dos nuevas clases e interfaces: Una interface llamada IOperacionEmpleado, otra interface llamada IOperacionEmpresa; una clase llamada OperaciónEmpleado que implemente de IOperacionEmpleado. Por último, una clase llamada OperacionEmpresa que implemente de IOperacionEmpresa.
c. Crea la clase principal o de pruebas, puedes llamarla Main, y prueba las clases del paquete operaciones, creando atributos de las interfaces e instancias de las clases que ahí están (recuerda que de una interface no puedes crear instancias).
d. En la clase principal, puedes usar la consola (System) o gráficamente con JOptionPane, incluso swing. Creando un menú que te permita ingresar empresas, una vez creadas las empresas, puedes crear empleados y asignarles la empresa donde pertenecen. Y realizar otras operaciones como: consultar todas las empresas, todos los empleados, empleado por documento, calcular sueldo de empleado, contar cantidad de empleados en una empresa.
e. En IOperacionEmpleados, declara los siguientes métodos abstractos que resuelvan lo anterior solicitado en el menú para empresas (puedes sobreescribir el método toString() en la clase Empleado). En OperacionEmpleado implementa los métodos para que realicen dichas operaciones.
f. En IOperacionesEmpresa declara los métodos abstractos necesarios que resuelvan lo solicitado en el menú e impleméntalos en OperacionEmpresa.
