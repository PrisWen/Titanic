# Titanic
Este espacio fue creado para aprender sobre "Machine learning".
Mi análisis se describe de la siguiente manera:
La carga del dataset train.csv que se entrenara debe ser procesada de tal manera que se debe identificar las columnas que no tengan un valor significativo.
Entre las columnas que consideraría eliminar están: PassengerId,Name,Ticket,Cabin
Entre aquellas columnas que tienen varios valores vacíos como "Age", la reemplazare por la mediana.
La columna "Embarked" me parece peculiar porque solamente 2 campos no tienen valor, en este caso sería mejor eliminar esas 2 filas.
Luego realice la carga del dataset test.csv, eliminando los mismos campos que en la primera parte
Luego pongo como columna y los valores de sobrevivientes
Los valores que son cadenas los convierto a numéricos 
Me di cuenta que en test.csv también faltaban valores de “Age” y “Fare” y los reemplace por la media
Al contar las columnas también me di cuenta de que data_test tenía la columna “Survived” por demás y la eliminé
Luego decidí usar una clasificación de árboles, que salió con un resultado de gran porcentaje.

