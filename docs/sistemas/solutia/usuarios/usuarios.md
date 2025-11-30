---
layout: default
title: "Gestión de Usuarios"
parent: "Usuarios"
grand_parent: "Solutia"
nav_order: 1
---

# Gestión de Usuarios en Solutia

Este instructivo detalla los pasos para crear usuarios, asignar permisos y copiar favoritos en el sistema ERP Solutia.

## 1. Acceso al ABM de Usuarios

Para realizar un Alta, Baja o Modificación (ABM) de un usuario, debemos dirigirnos a la siguiente pestaña en el menú principal:

**Herramientas > Seguridad > Usuarios**

![Listado de Usuarios](/ALEDO-Docs/assets/usuarios/usuarios.png)

Una vez ingresado, veremos un listado completo de los usuarios existentes.
*   **Insert:** Crear un nuevo usuario.
*   **Suprimir:** Eliminar el usuario seleccionado.
*   **Ctrl + E:** Editar el usuario seleccionado.

También es posible utilizar los iconos del menú contextual superior para realizar estas acciones.

## 2. Crear un Nuevo Usuario

Al presionar **Insert** o el botón de agregar, se abrirá una ventana emergente.
1.  Completar los campos **Usuario** y **Nombre**.
2.  El resto de los campos pueden dejarse con sus valores por defecto.

![Agregar Usuario](/ALEDO-Docs/assets/usuarios/agregar.png)

### Establecer Contraseña
Para que el usuario pueda ingresar al sistema, es necesario asignarle una contraseña:
1.  Dirigirse a la opción de contraseña.
2.  Establecer una **contraseña provisoria**.
3.  Solicitar al usuario que cambie su contraseña en su primer ingreso.

![Setear Password](/ALEDO-Docs/assets/usuarios/setear_password.png)

## 3. Asignación de Permisos

Un usuario recién creado no podrá interactuar con ningún módulo hasta que se le asignen permisos.
La práctica recomendada es **copiar los permisos de un usuario existente** que tenga el mismo rol (hasta que se implemente la división por grupos de permisos).

1.  Seleccionar el usuario nuevo.
2.  Hacer clic en el botón **"Copiar Permisos"**.
3.  Elegir el **usuario modelo** (de quien queremos copiar los permisos).

![Copiar Permisos](/ALEDO-Docs/assets/usuarios/copiar_permisos.png)

## 4. Copiar Favoritos

Los favoritos son vistas resumidas con información importante que facilitan la tarea diaria. Podemos copiar los favoritos de un usuario a otro.

1.  Ingresar con el usuario que **ya posee** los favoritos configurados.
2.  Hacer clic en el enlace **"Editar Favoritos"**.
3.  Posicionarse sobre el favorito que se desea copiar.
4.  Presionar **Ctrl + I**.
5.  Elegir el **usuario destino** al cual se le copiará el favorito.

![Copiar Favorito 1](/ALEDO-Docs/assets/usuarios/copy_favorite.png)
![Copiar Favorito 2](/ALEDO-Docs/assets/usuarios/copy_favorite2.png)

> [!NOTE]
> El usuario destino deberá **reiniciar Solutia** para ver reflejados los cambios en sus favoritos.
