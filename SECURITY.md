# Seguridad

ApostAmo es un prototipo histórico basado en **puntos/diamantes virtuales**. No está diseñado ni auditado como plataforma de juego con dinero real.

## Baseline

- No guardar contraseñas, tokens, claves de sesión ni secretos en Git.
- Configurar secretos mediante variables de entorno.
- Revisar autenticación, cookies, CSRF y rate limiting antes de exponer el servicio.
- Proteger especialmente los endpoints que crean, transfieren o ajustan saldos virtuales.
- Toda modificación de saldo debe ser validada en servidor y quedar trazable.
- No confiar en valores de saldo, resultado o rol enviados por el cliente.
- Mantener backups y migraciones si se reutiliza una base de datos real.

## Alcance

No adaptar este código directamente a depósitos, retiros, premios monetarios o activos con valor sin una revisión legal, financiera y de seguridad específica.

## Reportes

Usar cuentas y datos sintéticos para reproducir problemas; no publicar credenciales ni datos personales.
