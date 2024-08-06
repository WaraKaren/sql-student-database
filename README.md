# Student Database

### [Learn SQL by Building a Student Database: Part 2](https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-2)

En el segundo tutorial, profundizarás en la administración y análisis
de bases de datos de estudiantes usando SQL y PostgreSQL. Aprenderás a
realizar consultas avanzadas mediante JOIN para combinar datos de múltiples
tablas y a utilizar funciones de agrupamiento (GROUP BY) y ordenamiento
(ORDER BY). Se cubrirán también las funciones agregadas para sumarizar
datos y la modificación de estructuras de tablas existentes con ALTER TABLE.
Esta parte incluye la creación de copias de seguridad y restauración
de bases de datos, y el uso de scripts Bash para una gestión más
eficiente y segura de tu entorno.

Haz clic [aquí para iniciar el segundo tutorial](https://gitpod.io/new/?autostart=true#CODEROAD_TUTORIAL_URL=https%3A%2F%2Fraw.githubusercontent.com%2FLaboratoria%2Flearn-sql-by-building-a-student-database-part-2%2Fmain%2Ftutorial.json,CODEROAD_DISABLE_RUN_ON_SAVE=true/https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-2)

## 4. Configuración del Ambiente de Desarrollo

Los tutoriales usan [Gitpod](https://gitpod.io/). Con Gitpod, las
desarrolladores pueden iniciar instantáneamente un entorno de desarrollo
completo con todas las herramientas y dependencias necesarias para
trabajar en su proyecto, lo que elimina la necesidad de configurar
manualmente el entorno en sus propias máquinas.

A continuación encuentras el paso a paso para trabajar con Gitpod.
Sin embargo puedes ver este [video](https://youtu.be/legfwHxU_cI)
que hemos preparado.

### Paso 1. Crea una cuenta en Gitpod usando Github

Para crear una cuenta en Gitpod utilizando GitHub, sigue estos pasos:

1. Dirígete al sitio web de Gitpod en [gitpod.io](https://www.gitpod.io/).
2. Haz clic en el botón "Login" en la esquina superior derecha de la página.
3. Selecciona la opción "Continue with GitHub".
4. Serás redirigido a la página de autorización de GitHub. Si no has iniciado
   sesión en GitHub, se te pedirá que lo hagas.
5. Después de iniciar sesión en GitHub, se te pedirá que autorices a Gitpod
   a acceder a tu cuenta de GitHub. Revisa los permisos y haz clic en
   "Authorize Gitpod" (Autorizar Gitpod).
6. Completa la informacion solicitada para compeltar el registro.
7. ¡Listo! Ahora tienes una cuenta en Gitpod vinculada a tu cuenta de GitHub.

### Paso 2. Crea un workspace para los tutoriales

1. En [Gitpod](https://gitpod.io/workspaces), haz clic en el boton "New Workspace".
2. En la opción "Select a repository" ingresa la url de repositorio del tutorial:
   - Tutorial 1: [https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-1](https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-1)
   - Tutorial 2: [https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-1](https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-2)
3. Verifica que en las demás campos esten elegidas las opciones "VSCode 1.90.2"
   y "Standar".
4. Haz clic en "Continue".
5. Gitpod abrirá VSCode con el nuevo espacio de trabajo y comenzará a configurar
   el entorno automáticamente.

### Paso 3. Inicia el tutorial

1. En el VSCode abierto por Gitpod, abre el menú hamburguesa (tres líneas
   horizontales en la esquina superior izquierda).
2. Ve al menú "View".
3. Haz clic en la opción "Command Palette".
4. Escribe "CodeRoad: Start" y elígelo entre las opciones para ejecutarlo.
5. Se abrirá un nuevo panel con el tutorial.

### Paso 4. Retomar un tutorial en el punto en el que lo dejé la última vez

1. Inicia sesón en [Gitpod](https://gitpod.io/workspaces) y lista los workspaces
2. En el workspace del tutorial que quieres retomar haz click en el
   menú de tres puntos.
3. Elige la opcion "Open"
4. Gitpod abrirá VSCode con el nuevo espacio de trabajo y comenzará a configurar
   el entorno automáticamente.
5. Inicia el tutorial de nuevo siguiendo el paso 3.

## 5. Entregable

Haz fork a este repositorio. Luego ajustar el README para registrar
todos los comandos ejecutados durante los tutoriales. Puede usar
el siguiente formato:

```md
# Tutorial 1

## Paso 1

   `echo sql Hello`

## Paso 2

   `psql --username=freecodecamp --dbname=psql`
```

Puedes obtener un historial de los comandos ejecutados en una terminal
con el comando `history`.

## 6. Consideraciones para pedir tu Project Feedback

Antes de agendar tu Project Feedback con tu coach, asegúrate de:

* [ ] Completar los 2 tutoriales propuestos
* [ ] Tener un fork con un entorno de Gitpod completo

## 7. Objetivos de aprendizaje


Reflexiona y luego marca los objetivos que has llegado a entender y aplicar en tu proyecto. Piensa en eso al decidir tu estrategia de trabajo.

### SQL

- [ ] **Realizar operaciones básicas de consulta de una base de datos utilizando las cláusulas SELECT y WHERE**

  <details><summary>Links</summary><p>

  * [Querying a Table](https://www.postgresql.org/docs/current/tutorial-select.html)
  * [SELECT reference](https://www.postgresql.org/docs/16/sql-select.html)
</p></details>

- [ ] **CREATE TABLE**

  <details><summary>Links</summary><p>

  * [SQL CREATE TABLE Statement - W3Schools](https://www.w3schools.com/sql/sql_create_table.asp)
</p></details>

- [ ] **INSERT**

  <details><summary>Links</summary><p>

  * [Inserting Data](https://www.postgresql.org/docs/current/dml-insert.html)
</p></details>

- [ ] **UPDATE**

  <details><summary>Links</summary><p>

  * [Updating Data](https://www.postgresql.org/docs/current/dml-update.html)
</p></details>

- [ ] **DELETE**

  <details><summary>Links</summary><p>

  * [DELETE](https://www.postgresql.org/docs/current/dml-delete.html)
</p></details>

- [ ] **Primary Key**

  <details><summary>Links</summary><p>

  * [Primary Keys](https://www.postgresql.org/docs/current/ddl-constraints.html#DDL-CONSTRAINTS-PRIMARY-KEYS)
</p></details>

- [ ] **Foreign key**

  <details><summary>Links</summary><p>

  * [Foreign Keys](https://www.postgresql.org/docs/current/ddl-constraints.html#DDL-CONSTRAINTS-FK)
</p></details>

- [ ] **ALTER TABLE**

  <details><summary>Links</summary><p>

  * [Modifying Tables](https://www.postgresql.org/docs/current/ddl-alter.html)
</p></details>

- [ ] **Comprender y utilizar cláusulas JOIN para combinar datos de múltiples tablas.**

  <details><summary>Links</summary><p>

  * [Joins Between Tables](https://www.postgresql.org/docs/current/tutorial-join.html)
</p></details>

- [ ] **Condensar resultados con cláusulas de agrupación de datos como GROUP BY y HAVING**

  <details><summary>Links</summary><p>

  * [SELECT reference](https://www.postgresql.org/docs/16/sql-select.html)
  * [Aggregate Functions](https://www.postgresql.org/docs/current/tutorial-agg.html)
</p></details>

- [ ] **Ordernar el resultado utilizando la cláusula ORDER BY**

  <details><summary>Links</summary><p>

  * [SELECT reference](https://www.postgresql.org/docs/16/sql-select.html)
</p></details>

- [ ] **Trabajar con funciones de agregación como COUNT, SUM, AVG, MAX y MIN**

  <details><summary>Links</summary><p>

  * [Aggregate Functions](https://www.postgresql.org/docs/current/tutorial-agg.html)
</p></details>

- [ ] **Constraints**

  <details><summary>Links</summary><p>

  * [Constraints](https://www.postgresql.org/docs/current/ddl-constraints.html)
</p></details>

### Virtual Machines

- [ ] **Virtual Machines Setup**

  <details><summary>Links</summary><p>

  * [Creating a Virtual Machine - Oracle VM](https://docs.oracle.com/en/virtualization/virtualbox/6.0/user/vboxmanage-createvm.html)
  * [Setting Up a Virtual Machine - Microsoft](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/quick-create-virtual-machine)
</p></details>

### PostgreSQL

- [ ] **PostgreSQL Setup**

  <details><summary>Links</summary><p>

  * [PostgreSQL Installation - PostgreSQL Docs](https://www.postgresql.org/download/)
  * [How To Install and Use PostgreSQL on Ubuntu - DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-20-04)
</p></details>

- [ ] **PostgreSQL Commands**

  <details><summary>Links</summary><p>

  * [PostgreSQL psql Commands - PostgreSQL Docs](https://www.postgresql.org/docs/current/app-psql.html)
  * [Commonly Used PostgreSQL Commands - Verta.ai](https://www.verta.ai/resources/tutorials/database/postgresql-commands)
</p></details>

- [ ] **PostgreSQL Backup**

- [ ] **PostgreSQL Restore**

### Shell

- [ ] **Shell Scripts**

  <details><summary>Links</summary><p>

  * [Shell Scripting Guide - LinuxCommand.org](http://linuxcommand.org/lc3_writing_shell_scripts.php)
</p></details>

- [ ] **File Permissions**

  <details><summary>Links</summary><p>

  * [Understanding Linux File Permissions - DigitalOcean](https://www.digitalocean.com/community/tutorials/understanding-linux-file-permissions)
  * [File Permissions in Linux - Red Hat](https://www.redhat.com/sysadmin/linux-file-permissions)
</p></details>
