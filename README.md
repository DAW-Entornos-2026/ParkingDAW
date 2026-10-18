# ParkingDAW
Software en PSeInt para la gestión del aparcamiento ParkingDAW (3 plantas). Incluye control de barreras, panel de ocupación por planta, contratación de limpieza y cajero de cobro automático. Desarrollado con metodología Scrumban en GitHub Projects.

**Código base**

```
Algoritmo ParkingDAW_Master
	
	// =========================================================================
	// DECLARACIÓN E INICIALIZACIÓN DE VARIABLES GLOBALES
	// =========================================================================
	Definir plazasTotales, plazasOcupadas, vehiculosAtendidos, ticketCorrelativo Como Entero
	Definir recaudacionEstancia, recaudacionServicios Como Real
	Definir ticketPagado Como Logico
	Definir opcionMenu Como Entero
	
	// Valores iniciales según plantilla maestra
	plazasTotales <- 40
	plazasOcupadas <- 0
	vehiculosAtendidos <- 0
	recaudacionEstancia <- 0.0
	recaudacionServicios <- 0.0
	ticketCorrelativo <- 100
	ticketPagado <- Falso
	
	// =========================================================================
	// BUCLE PRINCIPAL DE NAVEGACIÓN Y MENÚ
	// =========================================================================
	Repetir
		Escribir ""
		Escribir "=================================================="
		Escribir "    SISTEMA DE GESTIÓN CENTRALIZADA ParkingDAW    "
		Escribir "=================================================="
		Escribir "1. Registro de Entrada según Tipo de Vehículo"
		Escribir "2. Panel de Ocupación por Plantas y Estado"
		Escribir "3. Contratación de Servicio de Lavado"
		Escribir "4. Tarifa por Minutos, Cobro con IVA y Desglose"
		Escribir "5. Arqueo de Caja, Penalizaciones e Informes"
		Escribir "0. Salir del programa"
		Escribir "--------------------------------------------------"
		Escribir "Seleccione una opción (0-5):"
		Leer opcionMenu
		Escribir ""
		
		Segun opcionMenu Hacer
			1:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión en Code Review."
				
			2:
				// TODO: [Issue #3] Implementado por Developer 2
				Escribir "[PENDIENTE] Caso 2 no integrado. Esperando revisión en Code Review."
				
			3:
				// TODO: [Issue #4] Implementado por Developer 3
				Escribir "[PENDIENTE] Caso 3 no integrado. Esperando revisión en Code Review."
				
			4:
				// TODO: [Issue #5] Implementado por Developer 4
				Escribir "[PENDIENTE] Caso 4 no integrado. Esperando revisión en Code Review."
				
			5:
				// TODO: [Issue #6] Implementado por Developer 5
				Escribir "[PENDIENTE] Caso 5 no integrado. Esperando revisión en Code Review."
				
			0:
				Escribir "Cerrando el sistema ParkingDAW... ¡Hasta pronto!"
				
			De Otro Modo:
				Escribir "[ERROR] Opción no válida. Introduzca un número entre 0 y 5."
		FinSegun
		
	Hasta Que opcionMenu = 0

FinAlgoritmo
```
