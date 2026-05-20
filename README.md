Algoritmo compra
	Definir m, d Como Real
	Escribir "Monto:"
	Leer m
	d <- 0
	Si m > 500 Entonces d <- 0.25
	Sino Si m > 200 Entonces d <- 0.15
	Sino Si m > 100 Entonces d <- 0.10
	FinSi FinSi FinSi
	Escribir "Total a pagar: $", m*(1-d), " (descuento: $", m*d, ")"
FinAlgoritmo
