# Student Database

Para la practica usamos [Gitpod](https://gitpod.io/).


### url de los repositorio del tutorial:
   - Tutorial 1: [https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-1](https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-1)
   - Tutorial 2: [https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-1](https://github.com/Laboratoria/learn-sql-by-building-a-student-database-part-2)

### Pasos impotantes 


```md
# Tutorial 1

## Para cconectarnos a sql
   `psql --username=freecodecamp --dbname=psql`

## observamos la base de datos con:
      \l

## para conectarse a la base de datos usamos el comando seguido del nombre de la base de datos:
      \c students

## para visualizar las tablas usamos el comando:
      \d

## para limitar caracteres
### ejemplo limitar a un caracter 50:
      varchar(50)

## se realizo la combinacion de las tablas de major_id en students y en de majors:
      ALTER TABLE students ADD FOREIGN KEY(major_id) REFERENCES majors(major_id);

## haemos un bucle while para psar los datos uno por uno tenimos que realizarlo en nano
#!/bin/bash

#Script to insert data from courses.csv and students.csv into students>

cat courses.csv | while read MAJOR COURSE
do 
        echo $MAJOR
done



```

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
