# Consultas1-SQL

#CONSULTA SQL

## Tabla usuario

![tabla usuario](img/captura.png "Tabla usuario")

1. Para visualizar toda la información que contiene la tabla `usuario` se puede incluir con la instrucción SELECT el carcter '*' o cada uno de los campos de la tabla 

`select * from usuario`

![Consulta 1](img/2.png "Consulta 1")

2. Visualzar solamente la identificación del usuario

`select identificación from usuario`

![Consulta 2](img/3.png "Consulta 2")

3. si se desea obtener ls registros cuya identificación sean mayores o iguales a 150; se debe utilizar la clausula WHERE que especifica las condiciones que deben los registros que se van a seleccionar.

`SELECT * FROM Usuario WHERE Identificacion>=150`

![Consulta 3](img/4.png "Consulta 3")