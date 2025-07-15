# Tera Guía (classic) Español

## Parche v31.04 Y v33.08 (Akeron/Nova)

### :star: Compatible con TERA Toolbox para el parche 31.04

* Totalmente compatible con [TERA Toolbox para el parche 31.04](https://github.com/tera-classic-toolbox/tera-toolbox).
  Instalación automática desde la pestaña **Obtener más Mod**.

### :star: Compatible con TERA Toolbox para el parche 33.08 (Akeron/Nova)

* La información está disponible en Discord: <https://discord.gg/uCgpcmvpfp>

### :information_source: Instalación manual

El módulo Tera-Guía y [tera-guide-core](https://github.com/tera-classic-mods/tera-guide-core) ya son compatibles con este parche.
Para que las guías funcionen, necesita obtener versiones compatibles de **library** (classic) and **tera-guide-core** (classic):

1. Descargue **library** desde **[aquí](https://github.com/tera-classic-toolbox/library/archive/refs/heads/master.zip)** y colóquelo en la carpeta **mods** carpeta llamada como **"library"**.
2. Descargue **tera-guide-core** desde **[aquí](https://github.com/tera-classic-mods/tera-guide-core/archive/refs/heads/master.zip)** y colóquelo en la carpeta **mods** carpeta llamada uns **"tera-guide-core"**,
   No "tera-guide-core-master".

---

## Descripción

Un módulo de guía para TERA traducido al español. Muestra mensajes en la pantalla y dibuja zonas de ataques y mecánicas de jefes (también admite mensajes de texto a voz). Idiomas disponibles en Español y Ingles (detecta automáticamente).

## Dependencias

* **library** - <https://github.com/tera-classic-toolbox/library>
* **tera-guide-core** - <https://github.com/tera-classic-mods/tera-guide-core>

Al usar TeraToolbox, todas las dependencias se instalarán automáticamente.

## Comandos

| Toolbox(/8)                                                           | Descripción del comando                                                          |
| --------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| **guia**                                                              | Módulo on/off                                                                    |
| **guia&nbsp;gui**                                                     | Mostrar interfaz GUI.                                                            |
| **guia&nbsp;voice**<br>(defecto: desactivado)                         | Mensajes de texto a voz (TTS).                                                   |
| **guia&nbsp;lNotice**<br>(defecto: desactivado)                       | Enviar mensajes en el canal **Notice** en lugar de mensajes en pantalla.         |
| **guia&nbsp;gNotice**<br>(defecto: desactivado)                       | Enviar mensajes en el canal **Party**.                                           |
| **guia male~female**<br>(defecto: femenino)                           | Configure el género de voz de voz TTS (si está disponible).                      |
| **guia&nbsp;`auto`/`en`/`es`**<br>(default: es)                       | Establecer idioma de la guía.                                                    |
| **guia&nbsp;`1`~`10`**<br>(defecto: 2)                                | Configure la velocidad de voz TTS.                                               |
| **guia&nbsp;spawnObject**<br>(defecto: activado)                      | Generación de objetos marcadores.                                                |
| **guia&nbsp;stream**<br>(defecto: desactivado)                        | Modo Streamer (ocultar todos los mensajes y objetos, se reproducirá la voz TTS). |
| **guia&nbsp;dungeons**                                                | Lista de todas las dungeons compatibles y sus identificadores.                   |
| **guia&nbsp;verbose&nbsp;`id`**<br>(defecto: activado para todos)     | Enviar mensajes para la dungeon especificada por `id`.                           |
| **guia&nbsp;spawnObject&nbsp;`id`**<br>(defecto: activado para todos) | Generación de objetos marcadores para la dungeon especificada por `id`.          |
| **guia&nbsp;help**                                                    | Lista de comandos compatibles.                                                   |

## Dungeons Soportados

| ID                      | Nombre de la dungeon                        | Idioma  |
| ----------------------- | ------------------------------------------- | ------- |
| [9054](/guides/9054.js) | Bathysmal Rise (Difícil)                    | Español |
| [9056](/guides/9056.js) | Timescape (Difícil)                         | Español |
| [9057](/guides/9057.js) | Akeron's Inferno (Difícil)                  | Español |
| [9067](/guides/9067.js) | Demokron Factory (Difícil)                  | Español |
| [9068](/guides/9068.js) | Shadow Sanguinary (Difícil)                 | Español |
| [9754](/guides/9754.js) | Bathysmal Rise                              | Español |
| [9759](/guides/9759.js) | Forsaken Island (Difícil)                   | Español |
| [9768](/guides/9768.js) | Shadow Sanguinary                           | Español |

## Configuración de Mensajes

* En la pantalla (en la parte inferior) y mensajes de chat, si el parámetro **lNotice** está _activado_, todos los mensajes se enviaran al canal **Notice**. (**Mensajes en Chat Notice**).<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/9590b9f4-c7c3-4db7-982c-ae70cd2c5dab" alt="drawing" width="435"/>

* En la pantalla (en la parte superior), si el parámetro **lNotice** está _desactivado_, todos los mensajes se mostraran en la parte superior de la pantalla. (**Mensajes en Pantalla**).<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/cbad0e85-27cd-4ff7-a079-302c63580d5c" alt="drawing" width="435"/>

* Cuando el parámetro **gNotice** está _activado_, todos los mensajes se enviarán al canal **Party**. (**Mensaje en Chat Party**).<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/9dd3c39c-a802-40c7-86d1-706acaa19e0e" alt="drawing" width="435"/>

* Cuando el parámetro **stream** está _activado_, todos los mensajes de texto se enviarán solamente al canal de chat **Toolbox(/8)**, pero se reproducirán los mensajes de texto a voz TTS. (**Mensajes en Chat Toolbox**).<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/39b251f0-4818-475d-8357-9925f7b14184" alt="drawing" width="435"/>
* Escriba el comando **!guia help** para mostrar una lista completa de todos los comandos soportados y una lista de colores de textos en pantalla.<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/f9922fd7-d62d-4297-bc39-4e561cd3e384" alt="drawing" width="435"/>

* Cuando ingresa a una dungeon el modulo le notificará con un mensaje de bienvenida, donde tambien le mostrara informacion adicional para el uso de comandos.<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/d33cf5ab-5c64-4ca1-8bae-1b6afcd111f0" alt="drawing" width="498"/>

* Para desactivar o activar los mensajes de texto a voz TTS, use el comando **!guia voice**.<br>

* Para cambiar el género de la a voz TTS, use el comando **!guia `male`/`female`**.<br>

* Para **cambiar a otro idioma**, use el comando **!guia `auto`/`en`/`es`**, o tambien puede utilizar la interfaz GUI y selecionar el idioma que desea.<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/f0806ac4-e2bb-48c4-b55d-61ec6997ef3f" alt="drawing" width="498"/>

## Interfaz GUI

* Escriba el comando **!guia gui** para mostrar una interfaz gráfica del modulo, puede tambien cambiar las configuraciones básicas.<br>
  <img src="https://github.com/Loliconera/tera-guide-spanish/assets/69399372/3d5b294b-03e7-4128-8eae-22f9a585ebbe" alt="drawing" width="498"/>

## Más información

* Wiki para desarrolladores [HSDN](https://github.com/hsdn/tera-guide-core/wiki)
* Para preguntas y sugerencias, comuníquese a través de Discord: **JKQ#5649**

## Créditos

* **[Kasea](https://github.com/Kaseaa)** - Desarrollador original del módulo Tera-Guide
* **[HSDN](https://github.com/HSDN)** - Autor original del módulo en inglés tera-guide HSDN
* **[michengs](https://github.com/michengs)** - Autor del código base para la mayoría de las guías y el núcleo del módulo
* **[ZC](https://github.com/tera-mod)** - Coordenadas proporcionadas para representar las áreas de ataque y la mecánica
* **[Kuroine](https://github.com/Kuroine)** - Autor del código base de la guía DA
* **[Multarix](https://github.com/Multarix)** - Autor de la guía RR y también realizando cambios en la traducción al inglés
* **[Owyn](https://github.com/Owyn)** - Desarrollador de grandes guías para RK-9, AA y GV, cuyo código se utilizó
* **[Loliconera](https://github.com/Loliconera)** - Autor de traducción al español latino
* **[Emilia](https://github.com/emilia-s2)** - Autora de traducción al portugués y guías de guardian
* **[ITunk](https://github.com/GrafNikola)** - Autor de la traducción inicial al ruso
