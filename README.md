# Curso-de-Python-
Ejercicios prácticos 
 construimos las tuplas poniendo sus elementos 
	# separados por comas entre dos paréntesis
	palos_baraja = ("corazones","diamantes","tréboles","picas")
	valores_baraja = ('A', 2, 3, 4, 5, 6, 7, 8, 9, 10, 'J', 'Q', 'K')
	as_de_picas = (valores_baraja[0], palos_baraja[3])
	reina_de_corazones = (valores_baraja[11], palos_baraja[0])
# podemos usar tuplas como elementos anidados dentro otra tupla
	mano = (as_de_picas, reina_de_corazones)
	print(mano)