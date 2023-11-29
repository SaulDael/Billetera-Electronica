# Billetera-Electronica
Desarrollo de una Aplicación Básica de Billetera Electrónica
# Objetivo: Comprender y aplicar conceptos de seguridad en transacciones financieras electrónicas, implementando una aplicación de billetera electrónica en Java. 
Duración: 1.5 horas 

# Instrucciones: 

#Parte 1: Definición de la Clase CuentaBancaria (30 minutos) 
- Crea una nueva clase llamada CuentaBancaria en tu entorno de desarrollo Java preferido. 
- Define los atributos titular (nombre del titular) y saldo (saldo actual). 
- Implementa un constructor que permita inicializar la cuenta con un titular y un saldo inicial. 

# Parte 2: Métodos de la Clase CuentaBancaria (30 minutos) 
- Agrega métodos a la clase CuentaBancaria: 
- getTitular(): Retorna el nombre del titular. 
- getSaldo(): Retorna el saldo actual. 
- depositar(double monto): Realiza un depósito en la cuenta y muestra el nuevo saldo. 
- retirar(double monto): Realiza un retiro si hay saldo suficiente y muestra el nuevo saldo. 
- obtenerHistorial(): Crea un método para obtener el historial de transacciones (puede ser un array o lista). 

# Parte 3: Seguridad en Transacciones (30 minutos) 
- Agrega un nuevo método depositarSeguro(double monto) a la clase CuentaBancaria: 
- Implementa la encriptación del monto utilizando SHA-256 antes de realizar el depósito. 
- Maneja las excepciones adecuadamente. 

#Parte 4: Diseño y Simulación de Transacciones (30 minutos) 
- Crea una clase Main con el método main: 
- Crea una instancia de CuentaBancaria con un nombre de titular y saldo inicial. 
- Realiza varias transacciones de depósito y retiro. 
- Muestra el historial de transacciones al final. 

# Entrega: 
- Sube tu código a una plataforma de control de versiones (por ejemplo, GitHub). 

# Prepara un breve informe que incluya: 
- Una descripción de la aplicación desarrollada. 
- Capturas de pantalla que muestren la ejecución de la aplicación con comentarios explicativos. 
- Breve reflexión sobre los desafíos enfrentados y cómo abordaste la seguridad en las transacciones. 
