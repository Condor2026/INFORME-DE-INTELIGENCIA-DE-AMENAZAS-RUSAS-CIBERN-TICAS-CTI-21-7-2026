# Guía para Contribuir

Gracias por tu interés en mejorar este repositorio de Inteligencia de Amenazas. Toda ayuda es valiosa para mantener actualizados los indicadores y proteger a los usuarios.

## ¿Cómo puedo contribuir?

### 1. Reportar un nuevo IOC
Si detectas un nuevo dominio, IP o hash que se relacione con `goo.su` o la IP `82.202.170.126`:

- Abre un **Issue** con la etiqueta `new-ioc`.
- Incluye la evidencia (captura de pantalla, link a VirusTotal, URL escaneada en urlscan.io).
- Especifica el tipo de amenaza (Phishing, C2, Dropper, etc.).

### 2. Mejorar el Análisis
Si encuentras un error en el dossier principal (`README.md`) o tienes más contexto sobre alguna de las campañas (Operation Hydra Bet, CyberVolk, etc.):

- Realiza un **Fork** del repositorio.
- Crea una rama (`git checkout -b update-analysis`).
- Realiza los cambios y envía un **Pull Request**.
- Asegúrate de citar tus fuentes.

### 3. Scripts y Herramientas
Si desarrollas un script para automatizar la verificación de estos IOCs o para bloquearlos en firewalls/EDRs:

- Agréguelo en una carpeta `/tools`.
- Documenta su uso en el README o en un archivo `.md` dentro de la carpeta.

## Código de Conducta
Mantén un tono profesional. Este repositorio está orientado a la defensa cibernética, no a actividades ofensivas. No compartas exploits funcionales o malware activo sin previa autorización y análisis.

## Actualizaciones Automáticas
Este repositorio se actualiza manualmente según la información disponible en fuentes abiertas (OSINT) y sandboxes. Si deseas colaborar con actualizaciones periódicas, contáctame para coordinar el acceso.
