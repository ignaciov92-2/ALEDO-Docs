---  
layout: default  
title: "Investigar Caja"  
parent: "Cajas"  
grand_parent: "Sistemas"  
nav_order: 2  
---

# Investigación de Logs Ante Sucesos Inesperados en Caja

Cuando una caja presenta comportamientos irregulares —errores, montos incorrectos, cierres inesperados o fallas operativas— es fundamental revisar los **logs del sistema** para identificar el origen del problema. Una investigación correcta permite resolver incidentes más rápido y aportar evidencia clara al soporte técnico.

---

## 📂 Ubicación de los Logs

Todos los registros generados por el sistema se almacenan en la ruta:

```
C:\DLR\SIG\logs
```

Dentro de esta carpeta, deben buscarse principalmente los archivos generados por el POS. Estos archivos utilizan un formato similar a:

```
POS0010-20251127
```

Donde:
- **POS0010** → Identificador de la caja.  
- **20251127** → Fecha del log (AAAAMMDD).

---

## 📝 Cómo Analizar los Logs

1. **Abrir el archivo** con *Bloc de Notas* o cualquier editor de texto.
2. Utilizar **Ctrl + B** o **Ctrl + F** para buscar palabras clave:
   - Montos
   - Códigos de operación
   - Términos como *error*, *fail*, *exception*, *offline*, etc.
3. Revisar los eventos alrededor del horario en el que ocurrió el suceso.
4. Identificar patrones como:
   - Cancelaciones de tickets
   - Transacciones incompletas  
   - Fallos de comunicación con Payway  
   - Errores de base de datos

Si el contenido no es claro, es recomendable **no interpretar equivocadamente** los eventos. En esos casos, el paso siguiente es contactar al soporte de DLR.

---

## ☎️ Contacto con Soporte Técnico

Siempre que no se logre identificar la causa del problema:

- Enviar los logs al soporte técnico de DLR.
- Acompañar con una breve descripción del suceso y horario aproximado.

Compartir los logs demuestra profesionalismo y acelera el diagnóstico.

---

## 🌐 Obtención Remota de Logs mediante Mesh Agent

Si no es posible acceder físicamente a la caja, también se pueden obtener los logs de forma remota:

1. Abrir **Mesh Agent**.  
2. Seleccionar la PC correspondiente a la caja.  
3. Navegar en su explorador de archivos remoto hacia:

   ```
   C:\DLR\SIG\logs
   ```

4. Descargar los logs necesarios sin interrumpir el funcionamiento de la caja.  
5. Analizar o reenviar al soporte como en el procedimiento anterior.

Esta herramienta permite acceder de manera rápida y ordenada a cualquier equipo registrado.

---

## 🖼️ Ejemplo de Carpeta de Logs

![Carpeta de Logs](/ALEDO-Docs/assets/logs/logs.png)

---

## ✔ Buenas Prácticas Generales

- Jamas editar los logs que estan en la pc objetivo.
- Descargar si lo que se desea es analizar y recortar eventos de interes, jamas modificar un archivo original.  
- Verificar que la fecha del archivo coincida con el incidente reportado.  
- Documentar cada hallazgo para llevar un historial de incidentes.  

---
