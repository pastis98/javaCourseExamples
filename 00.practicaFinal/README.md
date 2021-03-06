## Práctica Final. Programación Orientada a Objetos. 
### Desarrollo de un software pseudo-comercial con interfaz gráfica 
Aplicación desarrollada en Swing que gestione un tipo cualquiera de objeto (a elegir por el alumno) con persitencia en disco. 

#### Fecha de entrega:

Presentación final: 24 de mayo

#### Descripción de la práctica A:

Desarrollar una aplicación gráfica desarrollada en Swing que gestione un tipo cualquiera de objeto (a elegir por el alumno) con persitencia en disco.

La aplicación a desarrollar debe cumplir con los siguientes requisitos funcionales:

- Altas/Bajas/Modificaciones de objetos.
- Generación de listados en función de dos criterios de filtrado introducidos por el usuario. (P.e: mostrar todas las personas, sólo las que vivan en XXXX o las que vivan XXXX y estén casadas)
- Exportación de la información del programa a un fichero TXT gracias a la API suministrada por el profesor.
Es obligatorio emplear nuevos componentes gráficos (JTable, JComboBox, JTabbedPane, etc.) que se facilitan en la documentación de la asignatura.

#### Descripción de la práctica B:

Desarrollar un Power Point.

#### Evaluación de la práctica: Todos los alumnos parten de un 9.0. Nota mínima: 0. Nota máxima: 10.5.

- Funcionalidad: ¿Realiza toda la funcionalidad solicitada? - SI/NO. 
```
    Si (funcionalidadCompleta == NO) nota = 0;
```    
- Funcionalidad: ¿Cubre una necesidad real? ¿Podría llegar a vender/regalar este desarrollo a alguien? - SI/NO. 
```
    Si (necesidadReal == NO) nota -= 1.5ptos;
```    
- Funcionalidad: ¿Se utilizan componentes nuevos no impartidos en clase? - SI/NO ¿Cuál es el grado de dificultad que presentan? - (0 -bajo-, 0,75 -medio- ó 1,5 -alto-). 
```
    Si (componentesNuevos == NO) nota = 0; Else nota += gradoDificultad;
```    
bajo: ImageIcon, JComboBox, JTabbedPane, etc.
medio: JList, JCheckBox, JRadioButton, etc.
alto: JTable, JTree, etc.
- Funcionalidad: ¿Presenta algún error de ejecución? 
```
    Si (errores == SI) nota -= 1.5ptos;
```    
- Usabilidad: ¿Se ejecuta/inicia de una forma sencilla para el usuario? 
```
    Si (inicioSencillo == NO) nota -= 1pto
```    
- Usabilidad: ¿Posee una interfaz fácil de utilizar y amigable como las aplicaciones de escritorio que estamos acostumbrados a utilizar (2 -no-, 1 -más o menos- ó 0 -si-)? 
```
    nota -= factorDeUsuabilidad;
```    
- Diseño: ¿El diseño de la práctica sigue con los patrones (MVC, DAO, Experto, etc.) y estrategias (DRY, KISS, etc.) de diseño explicadas en clase? 
```
    Si (diseño == MALO) nota -= 1.5ptos; Else Si (diseño == REGULAR) nota -= 0.75ptos;
```
 

 ### Sprint 1: Modelo de objetos

 Programación de la lógica de objetos con una clase Gestor que realice la funcionalidad básica con dichos objetos: búsqueda, creación, borrado, listados, etc.

 ### Sprint 2: Interfaz gráfica
 ### Sprint 3: Entrada y salida
 ### Sprint 4: Intrfaz gráfico mejorado