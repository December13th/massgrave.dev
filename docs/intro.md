---
slug: /
sidebar_position: 1
sidebar_label: Intro
---

# Microsoft Activation Scripts (MAS)

Activador de Windows y Office de código abierto que incluye métodos de activación HWID (Identificación de hardware), Ohook, TSforge, KMS38 y KMS en línea, junto con soluciones avanzadas para resolución de problemas.

---

### Cómo activar Windows / Office?

#### Método 1 - PowerShell (Windows 8 y versiones posteriores) ❤️

:::info

1.   **Abre PowerShell**  
	Para hacer eso, presiona la tecla de Windows + X, luego selecciona PowerShell o Terminal.

2.   **Copia y pega el código que está abajo, luego presiona Enter.**  
```
irm https://get.activated.win | iex
```
Alternativamente, puedes usar lo siguiente (esto será descontinuado en el futuro):
```
irm https://massgrave.dev/get | iex
```

3.   Verás las opciones de activación. Elige las opciones de activación que están resaltadas en verde. 

4.   Eso es todo.

:::

#### Método 2 - Tradicional (Windows Vista y versiones posteriores)

<details>
  <summary>Haz clic aquí para ver</summary>
  
1.   Descarga el archivo usando uno de los enlaces de abajo:  
`https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip`  
or  
`https://git.activated.win/massgrave/Microsoft-Activation-Scripts/archive/master.zip`
2.   Haz clic derecho sobre el archivo zip descargado y extráelo.
3.   En la carpeta extraída, busca la carpeta llamada `All-In-One-Version`.
4.   Ejecuta el archivo llamado `MAS_AIO.cmd`.
5.   Verás las opciones de activación. Sigue las instrucciones que aparecen en pantalla.
6.   Eso es todo.

</details>

---

- Para activar productos adicionales como Office para macOS, Visual Studio, RDS CALs y Windows XP**, Revvisa esto [here](unsupported_products_activation.md).
- Para ejecutar los scripts en unattended mode, Revisa esto [here](command_line_switches.md).

---

### No funciona ❓

- Si no puedes **iniciar MAS** usando el método de PowerShell, por favor consulta el **Método 2** arriba.
- Si **MAS** se inicia pero muestra errores, revisa los pasos para solución de problemas que están resaltados en azul y síguelos.
- Si los problemas persisten, no dudes en contactarnos. [here](troubleshoot.md).

---

:::Nota

- El comando IRM en PowerShell descarga un script desde una URL especificada, y el comando IEX lo ejecuta.
- Siempre verifica dos veces la URL antes de ejecutar el comando y confirma que la fuente sea confiable cuando descargues archivos manualmente.
- Ten precaución, ya que algunos distribuyen malware disfrazado como *MAS* cambiando la URL en el comando IRM.

:::

------------------------------------------------------------------------

## Última versión de **MAS**

Last Release - v3.4 (3-June-2025)  
[GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts) / [Azure DevOps](https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts) / [Self-hosted Git](https://git.activated.win/massgrave/Microsoft-Activation-Scripts)

------------------------------------------------------------------------

# Características

- Método **HWID (Licencia Digital)** para activar Windows de forma permanente
- Método **Ohook** para activar Office de forma permanente
- Método **TSforge** para activar Windows/ESU/Office de forma permanente
- Método **KMS38** para activar Windows hasta el año 2038
- Método **KMS en línea** para activar Windows/Office por 180 días (vigencia ilimitada con tarea de renovación)
- Solución avanzada de problemas de activación
- Carpetas $OEM$ para preactivación
- Cambiar edición de Windows
- Cambiar edición de Office
- Verificar estado de activación de Windows/Office
- Disponible en versiones todo en uno y archivos separados
- Totalmente de código abierto y basado en scripts batch
- Menos detecciones por antivirus

------------------------------------------------------------------------

## Resumen de activaciones

| Tipo de activación | Producto compatible | Período de activación                |Se requiere Internet?|
|:----------------|:-----------------------|:-------------------------------------|:--------------------|
| HWID            | Windows 10-11          | Permanente                            | Si                  |
| Ohook           | Office                 | Permanente                            | No                  |
| TSforge         | Windows / ESU / Office | Permanente                            | Si, Necesario en la versión 19041 y posteriores |
| KMS38           | Windows 10-11-Server   | Hasta el año 2038                   | No                  |
| Online KMS      | Windows / Office       | 180 días, pero se puede renovar para que dure toda la vida | Si                 |

Para más detalles, utiliza la información correspondiente de activación en los Docs y:  [comparison chart](chart.md).  
Para activar productos no soportados como Office en Mac, consulta [here](unsupported_products_activation.md).

------------------------------------------------------------------------

## Capturas de pantalla

![](/img/MAS_AIO.png)

![](/img/MAS_HWID.png)

![](/img/MAS_Ohook.png)

![](/img/MAS_TSforge.png)

![](/img/MAS_Troubleshoot.png)

![](/img/MAS_change_windows_edition.png)

![](/img/MAS_change_office_edition_1.png)

![](/img/MAS_change_office_edition_2.png)

![](/img/MAS_change_office_edition_3.png)

------------------------------------------------------------------------

Hecho con amor ❤️
