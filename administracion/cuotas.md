# Cuotas

## Configurar las cuotas

1. Entra a **Administración > Finanzas > Configuración de aportaciones**.
2. Captura o ajusta los campos:
   * **Monto de la aportación**: monto que se cobrará por propiedad en cada periodo.
   * **Cada cuántos meses**: frecuencia del ciclo. Ejemplo: `1` mensual, `2` bimestral, `3` trimestral.
   * **Mes inicial**: mes donde empieza el primer ciclo. Ejemplo: `1` enero, `12` diciembre.
   * **Día del periodo para generar cuotas**: día del ciclo en que se prepara o genera la cuota. Debe ser `1` o mayor.
   * **Días para vencimiento**: días después de generar la cuota para definir su fecha de vencimiento.
   * **Periodo al que pertenece**: define si la cuota corresponde al periodo **Anterior**, **Actual** o **Siguiente**.
   * **Modalidad**:
     * **Automática con revisión**: el sistema prepara la generación y permite revisarla antes de crear las órdenes de pago.
     * **Automática sin revisión**: el sistema genera las cuotas automáticamente sin revisión manual.
3. Presiona **Guardar configuración**.
4. Si el guardado fue correcto, aparecerá el mensaje **Configuración guardada**.

## Ver generaciones de cuotas

1. Entra a **Administración > Finanzas > Generaciones de cuotas**.
2. Revisa la lista de generaciones.
3. Cada generación muestra:
   * Concepto de la cuota.
   * Periodo: fecha inicial y fecha final.
   * Fecha en que fue preparada.
   * Estado:
     * **Pendiente de revisión**: todavía puede modificarse y generarse.
     * **Generado**: ya se crearon las órdenes de pago.

## Ver, modificar y aprobar cuotas generadas

1. En **Generaciones de cuotas**, selecciona una generación en estado **Pendiente de revisión**.
2. Revisa el concepto, periodo y **Fecha de vencimiento**.
3. Si necesitas cambiar el vencimiento:
   * Selecciona una nueva fecha.
   * Presiona **Guardar fecha de vencimiento**.
4. Revisa la lista de propiedades incluidas.
5. Para modificar una propiedad:
   * Toca la propiedad.
   * Ajusta el **Monto**, si corresponde.
   * Activa **Omitir propiedad** si no debe generarse cuota para esa propiedad.
   * Presiona **Guardar cambios**.
6. Cuando todo esté correcto, presiona **Generar cuotas**.
7. Confirma con **Sí, generar**.

Al confirmar, el sistema crea órdenes de pago para todas las propiedades aprobadas. Las propiedades omitidas no generan orden de pago.

## Consultar una generación ya aprobada

1. Entra a **Generaciones de cuotas**.
2. Abre una generación con estado **Generado**.
3. Consulta el resumen:
   * **Generado**: total aprobado y convertido en órdenes de pago.
   * **Omitido**: total omitido.
   * Fecha en que se generó.
4. En este estado ya no se pueden editar montos, omisiones ni fecha de vencimiento.

## Recomendaciones

* Usa **Automática con revisión** cuando quieras validar montos, vencimiento u omisiones antes de crear órdenes de pago.
* Usa **Automática sin revisión** solo si la configuración ya está validada y el proceso no requiere aprobación manual.
* Antes de presionar **Generar cuotas**, confirma que la fecha de vencimiento y las propiedades omitidas sean correctas.
* Una vez generadas las cuotas, la generación queda bloqueada para edición.
