# Rutina de actualización quincenal

## Este enlace público

El sitio usa exclusivamente una base sintética definida en index.html; no carga archivos ni se conecta a Odoo. La agenda se recalcula al abrir. Sirve para presentar el modelo, no para publicar datos de clientes.

## Actualizar el análisis real

1. En Odoo, exportá el lote completo y actualizado de órdenes y comprobantes. Incluí facturas, notas de crédito, internos, reversos y borradores, junto con los campos usados en los controles.
2. Guardá los nuevos Excel en la carpeta entradas del proyecto privado y retirà de esa carpeta el lote del corte anterior para no mezclar fotografías.
3. Ejecutá ACTUALIZAR.cmd, elegí la carpeta de exportación e indicá la fecha de corte.
4. Revisá el resumen, duplicados, conciliación orden-documento y cambios entre cortes. Si un control no cierra, investigá antes de distribuir.
5. Revisá el dashboard e informe local; conservá respaldo del histórico y las fuentes con sus huellas SHA-256.
6. Compartí el tablero real en un espacio privado con autenticación individual. No subas exportaciones Odoo, informes, bases ni datos reales al repositorio público Laboratorio.

## Privacidad

El repositorio y Pages son públicos: cualquiera puede ver HTML, código y datos publicados. Pages no brinda inicio de sesión privado para clientes. Para presentar información real se necesita alojamiento protegido por autenticación o informes con permisos controlados. No considerar privado el sitio Pages por cambiar la visibilidad del repositorio.

## Controles por corte

- Confirmar alcance del lote, fecha de corte y registros por archivo.
- Revisar claves duplicadas, negativos, notas de crédito y reversos.
- Conciliar circuitos fiscal e interno, saldos, órdenes completadas y vínculos económicos.
- Separar hechos, alertas e hipótesis; una alerta no acredita fraude.
- Conservar fuentes, resultados y decisiones de revisión para repetir el análisis.
