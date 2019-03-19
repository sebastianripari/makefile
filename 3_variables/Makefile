# Aqui creamos nuestra primer variable,
# 'CC' y le asignamos el valor 'gcc'.
# Luego el contenido de esta se usa de la
# siguiente forma: '${CC}'.

CC = gcc

# Como ya hemos dicho, lo que hay despues
# de los dos puntos se llama prerequisito
# por lo tanto sino se cumple, se arrojara
# un error. Por lo tanto en este caso debe
# existir el  archivo 'hello.c'.
hello: hello.c
	${CC} hello.c -o hello