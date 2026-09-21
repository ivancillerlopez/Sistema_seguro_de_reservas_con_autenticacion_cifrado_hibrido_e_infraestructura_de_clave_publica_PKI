# Sistema seguro de reservas con autenticación cifrado híbrido e infraestructura de clave pública PKI
Tecnologías: Python - Criptography - AES-256-GCM - RSA-OAEP - RSA-PSS - Scrypt - X.509: Autenticación:
- Scrypt con salt aleatorio y almacenamiento seguro de credenciales.
- Cifrado híbrido: AES-256-GCM (AAD) + RSA-OAEP, con gestión de claves y certificados X.509 mediante CSR y Autoridad Certificadora.
- Firma digital: RSA-PSS con SHA-256.
