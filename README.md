# Guía para IDX: Proyecto base Web Scraper

A continuación se detallará brevemente como inicializar un proyecto base en IDX para el desafío de Web Scraping elaborado por EY.

La meta es recolectar noticias de la página de "El Comercio" para obtener información relevante sobre tópicos en específico.

## Prerequisitos

- Tener una cuenta de Google
- Acceso a https://elcomercio.pe

## Configuración del ambiente

### 1. Ingresar al link: https://idx.dev
### 2. Darle click al botón "Get Started" e ingresar a su cuenta de Google.
### 3. Buscar y crear la plantilla de Pyhton con Flask (Categoría Backend).
### 4. Instalar dependencias

Para este proyecto instalaremos 2 dependencias. Para ello, en la consola ingresaremos los siguientes comandos

```bash
pip install beautifulsoup4
pip install requests
```
# Guía para Choco: Proyecto base Web Scraper

### 1. Ingresar a powershell
### 2. Ejecutar el siguiente comando
```bash
set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
### 3. Una vez instalado, ejecutar el siguiente comando.
```bash
choco install python38
```
### 4. Instalar dependencias con los siguintes comandos

```bash
pip install beautifulsoup4
pip install requests
```

#### Listo! El proyecto base ha sido creado ;)
