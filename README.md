# ApostAmo

Plataforma web experimental de **apuestas amistosas con diamantes virtuales**, creada dentro del ecosistema DesarrollAMO.

## Estado

**Prototipo histórico.** El repositorio contiene una implementación Flask con base de datos, templates, assets y configuración de despliegue. No se presenta como servicio de apuestas con dinero real.

## Alcance original

- cuentas de usuario;
- saldo de diamantes virtuales;
- creación de apuestas amistosas;
- participación entre usuarios;
- rol/enlace de juez para resolver resultados;
- historial;
- UI responsive;
- backend Flask y persistencia SQLite.

## Importante

Los “diamantes” son **puntos virtuales del prototipo**. Este proyecto no debe adaptarse automáticamente a dinero real, depósitos, retiros o apuestas reguladas sin un análisis legal, de seguridad y de cumplimiento específico para la jurisdicción correspondiente.

## Stack histórico

- Python / Flask;
- SQLite;
- HTML/CSS/JavaScript;
- Render (`render.yaml`);
- `server.py` como entrada principal.

## Ejecución local

```bash
git clone https://github.com/amoedo7/ApostAmo.git
cd ApostAmo
python -m venv .venv
# activar entorno
pip install -r requirements.txt
python server.py
```

## Estructura

```text
ApostAmo/
├── server.py
├── src/
├── templates/
├── static/
├── requirements.txt
├── render.yaml
└── ActualizarGit.py
```

## Antes de reutilizarlo

Revisar autenticación, sesiones, dependencias, persistencia, rate limiting, CSRF, secretos, backups y cualquier endpoint que altere saldos virtuales.

La URL histórica de Render puede dejar de existir o apuntar a una versión distinta; no se considera fuente de verdad sin verificación.

## Licencia

El README anterior afirmaba MIT, pero no aparece un archivo `LICENSE` en la raíz actual. No asumir una licencia hasta definirla explícitamente.

---

**DesarrollAMO** · experimento de interacción social con puntos virtuales, preservado con su contexto.
