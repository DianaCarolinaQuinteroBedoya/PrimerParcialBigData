# PRIMER PARCIAL BIG DATA

*Universidad: Sergio Arboleda*
##Estudiantes: Diana Carolina Quintero Bedoya

## Parte II
*DatawareHouse AWS RDS (26 puntos)*
1.	Cargar la bd de employees de MYSQL en una Base de datos AWS RDS https://dev.mysql.com/doc/employee/en/employees-installation.html (5 puntos)
2.	Diseñar una BD de datos DatawareHouse usando el modelo dimensional de estrella que permita analizar las información de productos, clientes y órdenes de ventas trimestrales. (5 puntos)
3.	Crear la BD de Datawarehouse en una BD postgressql en AWS RDS.
4.	Cargar los datos en la BD de datos de Datawarehouse(se deben entregar los scripts o consultas generadas).(6 puntos)
5.	Realizar las siguientes consultas sobre la BD de DatawareHouse:(5 puntos)
   •	Trimestre con mayor número de ventas
   •	Cliente con mayor número de órdenes en los últimos 3 trimestres.
   •	Producto más vendido por Trimestre


##  Consultas generadas

```
*SHOW TABLES;*
```
```
*SELECT * FROM employees;*
```
```
*SELECT * FROM departments;*
```
```
*SELECT * FROM dept_emp;*
```
```
*SELECT * FROM dept_emp_latest_date;*
```
```
*SELECT * FROM current_dept_emp;*
```
```
*SELECT * FROM dep_manager;*
```
```
*SELECT * FROM salaries;*
```
```
*SELECT * FROM titles;*
```
