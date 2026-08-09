# Rol webserver

Instala y configura Nginx en AlmaLinux, renderizando una página index.html
parametrizada con Jinja2.
## Variables
- host_port (default 80): puerto donde escucha el sitio
- site_name (default "Servidor Web Automatizado - Grupo 6"): título mostrado en la página

## Dependencias
Ninguna. Requiere AlmaLinux/RHEL con acceso a repositorios dnf.
## Handlers
- restart nginx: se dispara cuando cambia index.html.
