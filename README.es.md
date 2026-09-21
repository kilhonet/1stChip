# 1stChip

**Las especificaciones y los controladores de tu PC de un vistazo.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. En caso de discrepancia, prevalece la [versión en coreano](README.ko.md).

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/1stchip?lang=es)

![1stChip screenshot](images/1stchip-ko.webp)

## Descripción

1stChip muestra lo que hay dentro de tu PC —CPU, placa base, tarjeta gráfica, multimedia, tarjeta de red y otros dispositivos— en una sola pantalla, junto con la versión y la fecha del controlador instalado para cada uno.

Funciona incluso en un Windows recién instalado: un dispositivo aparece en la lista con su fabricante aunque todavía no tenga controlador y el Administrador de dispositivos solo muestre «Dispositivo desconocido». Esto resulta muy útil justo después de una instalación limpia, cuando necesitas saber qué controladores faltan.

Solo descomprimir y ejecutar. Sin instalación, sin permisos de administrador y sin nada más que instalar.

## Características

- **Resumen del hardware en una pantalla** — CPU, placa base, tarjeta gráfica, multimedia, tarjeta de red y otros dispositivos, cada uno con el logotipo del fabricante.
- **Versión y fecha del controlador instalado** para cada dispositivo, debajo de su nombre.
- **Funciona sin controladores** — los dispositivos sin controlador también aparecen con su fabricante y se marcan con `!`.
- **Comprobación de actualizaciones de controladores** — la lista se compara con el servidor de 1stChip; cuando se conoce un controlador más reciente, el dispositivo se marca y una descripción emergente muestra la versión disponible.
- **Un clic hasta la página del controlador** — haz clic en la marca `!` para abrir la página del controlador de ese dispositivo.
- **Línea de sistema** en la parte inferior: frecuencia de la CPU, memoria total y edición/versión de Windows.
- **Los dispositivos duplicados se agrupan** — los dispositivos idénticos aparecen una sola vez como `(×N)`.
- **Portable** — un único EXE que puedes llevar en una memoria USB.
- **No requiere permisos de administrador.**
- **Sigue la configuración de Windows** — modo oscuro o claro según el tema de aplicaciones de Windows; idioma de la interfaz según el idioma de visualización de Windows (inglés, coreano).

## Descarga / Instalación

| Paquete | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/1stchip?lang=es) |
| Portable (ZIP) | [Descargar](https://down.kilho.net/1stchip?lang=es&nosetup) |

1stChip está disponible como aplicación **portable**: descarga el ZIP, descomprímelo donde quieras y ejecuta `1stChip.exe`; no hace falta instalar nada. También funciona sin problema desde una memoria USB.

## Uso

1. Ejecuta `1stChip.exe`. La lista de hardware aparece de inmediato.
2. Cada categoría muestra sus dispositivos; la primera línea es el dispositivo representativo y el resto se muestra en gris.
3. Debajo del nombre de cada dispositivo verás la versión y la fecha del controlador **instalado**.
4. Una marca amarilla `!` junto a un dispositivo significa una de estas cosas:
   - no hay ningún controlador instalado,
   - el dispositivo informa de un código de problema, o
   - se conoce un controlador más reciente; pasa el cursor para ver la versión.
5. **Haz clic** en la marca `!` para abrir en el navegador la página del controlador de ese dispositivo.
6. El panel inferior muestra la frecuencia de la CPU, el tamaño de la memoria y el sistema operativo.

Solo se ejecuta una instancia a la vez; si lo vuelves a abrir, la ventana existente pasa al frente.

## Configuración

No hay ventana de configuración. 1stChip sigue automáticamente la configuración de Windows:

| Elemento | Origen |
|---|---|
| Modo claro / oscuro | Windows *Configuración → Personalización → Colores → Modo de aplicación* |
| Idioma de la interfaz | Idioma de visualización de Windows (coreano → coreano, cualquier otro → inglés) |
| Formato de fecha | Localizado (`yyyy-mm-dd` en coreano, `mm-dd-yyyy` en inglés) |

## Requisitos

- Windows 10 o Windows 11, **64 bits**
- No requiere permisos de administrador
- La conexión a Internet es opcional: solo se usa para la comprobación de actualizaciones de controladores

## Actualizaciones

1stChip **no** se actualiza solo. Las nuevas versiones se publican manualmente tras una verificación interna y se anuncian en la [página de 1stChip](https://v2.kilho.net/1stchip). Consulta el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

**Historial de versiones**

| Versión | Fecha | Notas |
|---|---|---|
| 0.9.0 | 2026-09-18 | Primera versión |

## Licencia

1stChip es **Freeware**.

Puedes usarlo en cualquier lugar —en casa, en la oficina, en centros educativos y en organismos públicos— y redistribuirlo libremente en su forma sin modificar.

## Enlaces

- Sitio web: <https://v2.kilho.net/1stchip>
- Foro: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
