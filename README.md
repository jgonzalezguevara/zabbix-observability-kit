# Zabbix Observability Kit

Este repositorio contiene un **kit de herramientas** para desplegar Zabbix (server + agent2) en entornos Linux. Incluye ejemplos reales, buenas prácticas y una base lista para producción usando **Docker Compose**.

Este repositorio acompaña al libro  
**Curso Zabbix – Guía práctica de instalación, configuración y seguridad**  
([Amazon](https://www.amazon.es/dp/B0G4R5QYK6))

## Qué incluye

- Stack Zabbix completo (Server + Web + DB)
- Zabbix Agent 2
- Plantillas base y ejemplos reales
- Scripts útiles para administración
- Guías paso a paso

## Estado del proyecto

🏗️ **En construcción**  
Este repositorio irá creciendo con ejemplos reales y casos prácticos.

## Para quién es

- Administradores de sistemas
- DevOps / SRE
- Personas que empiezan con Zabbix y quieren hacerlo bien

## Licencia

MIT

---

# Cómo levantar Zabbix

Para poner en marcha Zabbix en tu máquina local, sigue estos pasos:

## Requisitos

1. **Docker**: Asegúrate de tener **Docker** instalado. Si no lo tienes, puedes instalarlo desde [aquí](https://www.docker.com/get-started).
2. **Docker Compose**: Este proyecto usa **Docker Compose** para levantar los contenedores. Si no lo tienes, puedes instalarlo desde [aquí](https://docs.docker.com/compose/install/).

## Pasos para ejecutar Zabbix:

1. **Clona el repositorio** en tu máquina local:
   
   ```bash
   git clone https://github.com/tu-usuario/zabbix-observability-kit.git
   cd zabbix-observability-kit

2. Levantar los contenedores de Zabbix usando Docker Compose:

   docker-compose up -d


3. Acceder a Zabbix: Una vez que los contenedores estén en marcha, abre tu navegador y ve a:

   http://localhost:8080


4. Iniciar sesión en Zabbix con las siguientes credenciales:

   Usuario: Admin

   Contraseña: zabbix


# Cómo parar Zabbix

   Para detener Zabbix y eliminar los contenedores, puedes usar:

   docker-compose down


   Esto detendrá todos los contenedores sin eliminar los datos.
