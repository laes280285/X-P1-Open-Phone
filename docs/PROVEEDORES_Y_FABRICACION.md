# Proveedores y plan de fabricación (referencias, no compras aprobadas)

La meta es que cualquier persona pueda pedir los componentes por internet sin acuerdos exclusivos ni herramientas industriales en casa.

- **Módulo de procesamiento:** [Radxa CM5](https://radxa.com/products/cm/cm5/) y sus recursos de referencia.
- **Módem 4G:** [SIMCom SIM7600-H](https://www.simcom.com/product/SIM7600X-H.html); confirmar SKU y VoLTE por operador.
- **Pantalla E-Paper:** [LILYGO T5S3 4.7"](https://github.com/Xinyuan-LILYGO/T5S3-4.7-e-paper-PRO), solo como referencia de desarrollo; no se ha elegido panel final.
- **PCB y ensamblaje:** [PCBWay](https://www.pcbway.com/) u otro proveedor. Se necesitarán KiCad, Gerber, BOM con MPN, pick-and-place y especificaciones de ensayo.
- **Carcasa impresa:** [PCBWay 3D Printing](https://www.pcbway.com/rapid-prototyping/3d-printing/) o impresión local; archivos STEP/STL aún no existentes.
- **CNC opcional:** aluminio premium con STEP/IGES y cotización; no necesario para la versión económica.
- **Comerciales:** AliExpress, LCSC, distribuidores oficiales y equivalentes regionales. No se ha verificado disponibilidad actual por vendedor.

## Paquete reproducible objetivo

`hardware/pcb/*.kicad_*`, archivos Gerber/drill, BOM y centroid, `hardware/enclosure/*.step` y `*.stl`, firmware MCU, imágenes Linux/Android, guías de programación y fotografías de montaje.

**No existe afiliación comercial ni patrocinio de las empresas citadas.** No comprar piezas todavía sin revisar compatibilidad, seguridad de baterías e importación.