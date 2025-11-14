# PIPOS Architecture

Documentación de la arquitectura del sistema de punto de venta PIPOS, definida usando LikeC4.

## Descripción

Este repositorio contiene la especificación arquitectónica del sistema PIPOS, incluyendo diagramas de contexto, contenedores y componentes según el modelo C4.

## Estructura

- `specification.c4` - Definición de elementos y estilos de la arquitectura
- `context/` - Diagramas de contexto del sistema
- `containers/` - Diagramas de contenedores
- `components/` - Definición de componentes
- `actors/` - Actores del sistema
- `views/` - Vistas generadas de la arquitectura

## Visualizar localmente

Requisitos:
- Node.js 16+
- npm

Instalación:

```bash
npm install
```

Ejecutar servidor de desarrollo:

```bash
npm run dev
```

Se abrirá en `http://localhost:61000`

## Generar exports

Exportar a PNG:

```bash
npm run export
```

Exportar a PNG con tema oscuro:

```bash
npm run dark
```

Exportar a JSON:

```bash
npm run export:json
```

## Validar arquitectura

```bash
npm run validate
```

## Despliegue

La arquitectura se despliega automáticamente a GitHub Pages mediante GitHub Actions en cada push a la rama `main`.

URL: https://pipos-dev.github.io/pipos-architecture/

## Herramientas

- [LikeC4](https://likec4.dev/) - Lenguaje y herramientas para arquitectura como código
- [C4 Model](https://c4model.com/) - Modelo de visualización de arquitectura de software
