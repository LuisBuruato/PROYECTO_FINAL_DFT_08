# Sprint 1

## 1. Crear el repositorio público y compartirlo con el equipo

### Descripción:
Para la implementación del proyecto desarrolló un repositorio público en GitHub, donde manejan y detallan cada una de las actividades en el desarrollo del proyecto, junto a la colaboración entre los miembros del equipo. Este repositorio funciona como el espacio de trabajo colaborativo en el que se almacenan cada uno de los recursos necesarios en el proyecto, siendo scripts, visulizaciones y toda la documentación.

Por otro lado, la implementación de control de versiones también es una parte importante dentro de la realización de un trabajo en conjunto. Con GITHUB podemos controlar ese historial de versiones en caso de errores o fallos dentro de cada script subido y modificado.

## 2. Identificar los archivos a usar y armar la estructura de carpetas a usar en el repositorio

### Descripción:

En esta etapa inicial del proyecto, fue crucial realizar una identificación clara y precisa de los archivos de datos que se ibas a implementar para llevar a cabo el análisis y las operaciones de la aerolínea. La correcta identificación y organización de estos archivos permiten un flujo de trabajo eficiente y minimizan el riesgo de errores durante el desarrollo.

Además, se definió una estructura de carpetas en el repositorio que facilitara la colaboración entre los miembros del equipo, organizando los archivos de forma lógica y asegurando que cada sección del proyecto tuviera su propio espacio dentro del repositorio. Este enfoque garantiza que los desarrolladores puedan trabajar en diferentes aspectos del proyecto sin interferencias, manteniendo una separación clara entre scripts, datos, documentación y otros recursos.

## 3. Creación de la Base de Datos

### 3.1 Creación de la Base de Datos

**Descripción:**

La base de datos es el pilar fundamental sobre el cual se desarrolló todo el sistema de análisis de datos para **Wings of the East**. En este proyecto, se optó por usar **SQL Server** como gestor de bases de datos por su robustez y capacidad para manejar grandes volúmenes de datos transaccionales.

El enfoque inicial fue crear una estructura de base de datos que permitiera almacenar de forma eficiente los datos de tiquetes, horarios, vuelos, manteniendo una trazabilidad clara de cada operación realizada en el sistema. Se buscó una arquitectura que permitiera realizar consultas rápidas y eficaces, que brindaran insights útiles para la toma de decisiones.

### 3.2 Identificación de Entidades y Tablas

**Descripción:**

La correcta identificación de las entidades y tablas fue crucial para el éxito del proyecto, ya que esto permitió la creación de un modelo de datos que reflejara con precisión las necesidades operativas y analíticas de **Wings of the East**. Durante este proceso, se analizaron todos los aspectos del negocio, desde ll compra de tiquetes hasta el retraso de los vuelos.

### 3.3 Creación de Tablas y Objetos SQL

**Descripción:**

Una vez definidas las entidades clave, el siguiente paso fue la creación de las tablas en **SQL Server**. Cada tabla fue diseñada para reflejar la estructura de las entidades previamente identificadas. Se aplicaron reglas de normalización para evitar redundancias de datos y asegurar que cada tabla se mantuviera consistente con el modelo de datos establecido.
## Punto 4: Identificar las entidades/tablas a usar en la BD

**Descripción:**

El éxito del proyecto depende en gran medida de la correcta identificación de las entidades y tablas que reflejan las operaciones comerciales de **Wings of the East**. En esta etapa, se llevó a cabo un análisis exhaustivo de los datos proporcionados por la empresa, con el objetivo de modelar el sistema de información a través de una base de datos robusta y eficiente que permitiera gestionar de forma adecuada los datos de los vuelos, horarios, tiquetes y demás.

## Punto 5: Crear las tablas y objetos SQL necesarios

**Descripción:**

Una vez identificadas las entidades principales y las tablas necesarias, el siguiente paso fue implementar estas tablas en la base de datos **SQL Server**. Este proceso incluyó la definición detallada de las columnas de cada tabla, así como la configuración de relaciones mediante claves foráneas, asegurando la integridad referencial de los datos.

## Punto 6: Crear el flujo que importe los datos a la base de datos

**Descripción:**

El proceso de creación del flujo que permita la importación de datos a la base de datos fue una de las etapas clave para garantizar la fiabilidad y la precisión en la gestión de la información dentro de **Wings of the East**. Este flujo de datos fue diseñado para cargar de manera eficiente los tiquetes, vuelos, horarios, entreo otros, permitiendo que la empresa tenga acceso a datos en tiempo real. El enfoque fue asegurar que los datos se procesaran, transformaran y cargaran en la base de datos con la máxima integridad y sin pérdida de información.

## 7. Validar que todos tengan acceso a dicha base de datos y que puedan extraer datos sin problemas

### Descripción:

Una vez establecida la base de datos SQL Server y cargados todos los datos, el siguiente paso clave fue garantizar que todos los miembros del equipo tuvieran acceso sin problemas a dicha base de datos y pudieran extraer los datos requeridos para el análisis en tiempo real.

Se realizaron pruebas de acceso y conectividad con cada miembro del equipo para verificar que todos pudieran interactuar con la base de datos a través de sus propios entornos locales y herramientas. Estas pruebas incluyeron la verificación de los permisos de lectura y escritura, asegurándose de que cada miembro pudiera realizar consultas SQL, extraer datasets, y ejecutar scripts para alimentar el análisis en Python y Power BI sin interrupciones.

Se generaron credenciales personalizadas para cada miembro del equipo, otorgando los permisos necesarios para asegurar que cada uno tuviera los privilegios adecuados para trabajar sobre la base de datos sin comprometer la integridad de la misma.
## 8. Crear el método de automatización de ingesta de datos nuevos

### Acción Realizada:

El equipo de **Wings of the East** implementó un método automatizado para la ingesta de datos nuevos que garantiza la actualización constante de la base de datos sin intervención manual. Este proceso es clave para mantener la integridad y actualidad de los datos en todo momento, asegurando que el sistema refleje la información más reciente, tanto en el análisis de inventarios como en las métricas de costos y los horarios de cada vuelo.

El flujo de automatización se estructuró en varias fases críticas, todas documentadas y validadas:

# **Entregables Sprint 2**

## Objetivo General del Sprint 2

El objetivo principal de este sprint fue desarrollar un informe interactivo y funcional en Power BI que permitiera a los usuarios realizar un análisis detallado de las operaciones de Wings of the East. El informe debía proporcionar visualizaciones claras y concisas de los datos clave, permitiendo tomar decisiones informadas basadas en métricas precisas.

Para lograr este objetivo, se realizaron una serie de pasos que abarcan desde la creación del archivo .pbix hasta la validación final del informe. Este sprint se enfocó en asegurar que todas las etapas, desde la importación de datos hasta la generación de reportes y gráficos, se llevaran a cabo con la máxima precisión y profesionalismo.

_____

## **1. Crear el archivo .pbix**

En el inicio del **Sprint 2**, el primer paso crítico fue la creación del archivo **.pbix** en **Power BI Desktop**. Este archivo es fundamental, ya que funciona como el contenedor que almacena todos los datos, cálculos, y visualizaciones necesarias para desarrollar el dashboard interactivo y los informes finales.

El archivo **.pbix** no solo es un archivo de datos, sino que también sirve como el entorno de desarrollo dentro del cual se lleva a cabo todo el trabajo de análisis, transformación de datos y diseño visual. Es aquí donde se establecen las conexiones a las distintas fuentes de datos, se crean las medidas calculadas utilizando el lenguaje **DAX**, y se diseñan los gráficos e informes que permiten a los usuarios finales interactuar de manera efectiva con los datos.
## **Punto 2: Importación de Datos a Power BI**

La importación de datos en Power BI fue un paso fundamental para comenzar a trabajar con la información disponible de **Wignd of the east** y dar inicio al análisis de los datos. Este proceso involucró la importación de archivos CSV, bases de datos SQL y otros orígenes de datos, de manera que se pudiera trabajar con ellos en el entorno de Power BI.

### **2. Importación de Datos a Power BI**

**Objetivo**: El objetivo de esta fase fue centralizar y cargar todos los datos relevantes en Power BI para realizar las transformaciones necesarias, análisis y posteriormente diseñar las visualizaciones interactivas.

## **3. Limpieza y Transformación de los Datos en Power BI**

El tercer paso en el desarrollo del **Sprint 2** fue la **limpieza** y **transformación** de los datos importados. Esta fase es crítica, ya que asegura que los datos estén libres de errores y en un formato que permita su análisis efectivo. A través de las herramientas de **Power Query** de Power BI, se realizaron diferentes transformaciones y operaciones de limpieza para preparar los datos para el análisis.

### **Objetivo**:
El objetivo de esta etapa fue realizar la limpieza y transformación de los datos, asegurando que todos los valores fueran correctos, sin duplicados, y en los formatos adecuados para su análisis. Además, se generaron columnas calculadas que agregaron valor a los reportes y medidas para el análisis posterior.

## **4. Creación de Medidas, Columnas Calculadas y Relaciones en Power BI**

En este punto del **Sprint 2**, nos centramos en la creación de **medidas DAX**, **columnas calculadas** y el establecimiento de **relaciones** entre las tablas de datos. Estos elementos son fundamentales para que **Power BI** pueda realizar cálculos y análisis de forma dinámica y precisa.

### **Objetivo**:
El objetivo principal de esta etapa fue generar medidas y columnas que permitieran realizar cálculos específicos que no estaban presentes en los datos crudos, así como definir las relaciones entre las tablas para habilitar un análisis cruzado. Con estas herramientas, se logró preparar los datos para su uso en las visualizaciones y gráficos del informe final.

## **5. Diseño de Dashboards y reporte en Power BI**

El diseño de reportes y gráficos es una fase crítica dentro del **Sprint 2**, ya que es el momento en el que los datos procesados se transforman en visualizaciones interactivas y accesibles que permiten la toma de decisiones basada en datos. En esta etapa, el equipo se concentró en crear un dashboard que no solo fuera visualmente atractivo, sino que también contara con la capacidad de proporcionar insights clave sobre los vuelos, retrasos e ingresos por vuelo en **Wings of the East**.

### **Objetivo del paso**:
El objetivo de este paso fue crear un conjunto de reportes y gráficos interactivos en **Power BI** que permitieran al equipo de **Wings of the East** analizar su rendimiento operativo a los largo del periodo seleccionado. Estos reportes ofrecen un análisis detallado sobre vuelos e ingresos, proporcionando al usuario final una herramienta que les permite identificar tendencias, patrones y áreas de mejora.
