# Si corremos el comando make solo el primer target es ejecutado.
# Esto es porque el primer target es el default.
# Esta es la razon de porque al primer target se le suele llamar "all",
# ya que luego ese se encarga de llamar a los demas targets.

# Podemos cambiar el target por default usando un "phony target" llamado .DEFAULT_GOAL
# .DEFAULT_GOAL := generate

say_hello:
	@echo "Hello World"

generate:
	@echo "Creating empty text files..."
	touch file-{1..10}.txt

clean:
	@echo "Cleaning up..."
	rm *.txt