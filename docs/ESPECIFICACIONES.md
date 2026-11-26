# X-P1 — Especificaciones de concepto (Rev.6)

> **Estado:** propuesta abierta. Estas especificaciones no están verificadas en un prototipo; dimensiones, autonomía y compatibilidad están sujetas a pruebas.

| Área | Objetivo |
|---|---|
| Diseño | Plegable tipo traductor electrónico clásico |
| Tamaño cerrado | Meta de 163 × 100 × 30–36 mm (pendiente de CAD) |
| Procesador | Radxa CM5 (RK3588S2) de 8 GB |
| SO | Linux ARM; Android y dual boot sujetos a integración |
| Memoria de sistema | eMMC del módulo CM5, variante por elegir |
| Almacenamiento extraíble | SSD NVMe M.2 2230, 512 GB de ejemplo, con tapa trasera independiente |
| Comunicación | Módem SIM7600G-H 4G LTE; validar bandas, IMS/VoLTE, llamadas y SMS |
| Pantalla interior | IPS táctil de ~4”, resolución final por elegir |
| Pantalla exterior | E-Paper táctil de ~4.7” para notificaciones y llamadas cerrado |
| Teclado | QWERTY de ~64–68 teclas |
| Controles | 2 sticks de bajo perfil con clic L3/R3, rueda scroll lateral, LT/LB/RB/RT |
| Posición gatillos | **Reverso de la base inferior**, nunca tapa de pantalla ni lomo |
| Cámaras | Interior ~5–8 MP; exterior ~8–13 MP con AF deseable |
| Audio abierto | 2 bocinas estéreo a ambos lados de pantalla interior + micrófono |
| Audio cerrado | Auricular/ranuras exteriores + micrófono exterior; contestar cerrado |
| Micrófonos | 2 principales (abierto/cerrado) + tercero para ruido opcional |
| Otras funciones | Wi-Fi, Bluetooth, FM, IR, USB-C, nano-SIM, microSD opcional |
| Batería | Cartucho Li-Po 1S protegido y extraíble, objetivo 7,000 mAh |
| Carga | Gestión en PCB con medición térmica, protección y power-path |
| Acabados | Gris aluminio/plástico; negro con líneas y marca naranja |

## Prioridades

1. Probar datos, SMS y **llamadas entrantes/salientes con la tapa cerrada** con un operador real.
2. Diseñar gestión de energía, batería segura y audio exterior.
3. Validar que las piezas quepan y no haya interferencias mecánicas o RF.
4. Conectar teclado, sticks, gatillos traseros, cámaras y pantallas.
5. Publicar archivos KiCad y CAD editables más guía de montaje, una vez revisados.

## Límites actuales
No existen todavía esquemáticos eléctricos validados, PCB fabricada, STL/STEP listo para producir, firmware integrado ni certificación. Los renders son imágenes conceptuales, no planos dimensionales.