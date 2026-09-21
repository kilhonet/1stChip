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

### Flujo básico

1. Ejecuta `1stChip.exe`. La lista de hardware aparece en unos segundos.
2. La lista está agrupada así: **CPU → Placa base → Tarjeta gráfica → Multimedia → Tarjeta de red → Otros dispositivos**. La primera línea de cada categoría es el dispositivo representativo; el resto sigue en gris.
3. Debajo del nombre de cada dispositivo verás la **versión y la fecha del controlador instalado**.
4. Una marca amarilla `!` indica que hay algo que revisar. Pasa el cursor para ver el motivo y **haz clic** para abrir en el navegador la página del controlador de ese dispositivo.
5. En la parte inferior de la ventana se muestran la frecuencia de la CPU, el tamaño de la memoria y la versión de Windows.

La lista se lee una vez al iniciar. Después de instalar un controlador, cierra y vuelve a ejecutar 1stChip para ver el resultado.

### La ventana

| Parte | Qué muestra |
|---|---|
| Logotipo | Logotipo del fabricante (iniciales si no tiene logotipo) |
| Nombre del dispositivo | El nombre asignado por Windows. Los dispositivos idénticos se agrupan como `(×2)` |
| Segunda línea | Versión · fecha del controlador instalado |
| `!` | Sin controlador / con problema / hay un controlador más reciente — pasa el cursor para saber cuál, haz clic para la página del controlador |
| Panel inferior | Frecuencia de la CPU (base) · tamaño de la memoria · sistema operativo |

### Cómo…

**Acabas de instalar Windows y no sabes qué controladores instalar**
Ejecuta 1stChip y busca los dispositivos marcados con `!`. Si al pasar el cursor aparece «No hay ningún controlador instalado», a ese dispositivo le falta el controlador. Haz clic en `!` para abrir la página del controlador, instálalo y vuelve a ejecutar 1stChip para comprobar que la `!` ha desaparecido. Si el PC no tiene Internet porque falta el controlador de red, usa 1stChip para ver el fabricante y el modelo de la tarjeta de red y descarga el controlador desde otro PC.

**El Administrador de dispositivos muestra un «Dispositivo desconocido»**
El Administrador de dispositivos no puede dar nombre a un dispositivo sin controlador, pero 1stChip identifica el fabricante y la categoría sin él. Busca el dispositivo en su categoría y haz clic en `!`.

**Comprobar si tus controladores están actualizados**
Cuando se conoce un controlador más reciente, el dispositivo recibe una `!` y al pasar el cursor se lee «Puedes actualizar a la versión x.x.x». Sin `!`, está al día hasta donde se sabe.

**Consultar las especificaciones del PC rápidamente**
Lee solo la primera línea (dispositivo representativo) de cada categoría y tendrás la CPU, el chipset de la placa base, la tarjeta gráfica, el sonido y la tarjeta de red de un vistazo, con el tamaño de la memoria y la versión de Windows en el panel inferior. Útil al redactar un anuncio de venta o al comparar con los requisitos recomendados de un juego.

**Varios dispositivos idénticos**
Los dispositivos idénticos se agrupan en una línea con un contador como `(×2)`. Los dispositivos estructurales de los que nunca hay que preocuparse —concentradores USB, puentes internos— se omiten de la lista.

**Revisar muchos PC**
1stChip no necesita instalación ni permisos de administrador, así que guárdalo en una memoria USB y ejecútalo en cada PC. No deja nada en el PC donde se ejecuta.

**En un PC sin Internet**
La lista de hardware y los detalles de los controladores instalados funcionan sin conexión. Solo las marcas de «controlador más reciente disponible» y la página del controlador que se abre al hacer clic en `!` necesitan Internet.

**La ventana está en modo oscuro (o claro), o en inglés**
1stChip sigue a Windows. Cambia el modo claro/oscuro en Windows *Configuración → Personalización → Colores → Modo de aplicación*, y el idioma de la interfaz mediante el idioma de visualización de Windows (coreano → coreano, cualquier otro → inglés).

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
