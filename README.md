# Maquetación - Proyecto Vega

## Resumen

La maquetación se realizó tomando como base el _preprocesador_ _Sass_ para poder usar funciones, mixins, variables, etcétera, lo cual permite tener un producto **escalable**.

### Para verificar el diseño

Es necesario abrir un editor de código (HTML), como por ejemplo _Visual Studio_ y ejecutar la opción **Open With Live Server** mientras el archivo HTML a revisar está seleccionado.

## Estructura

**Carpetas**:

- _css_ : Archivos generados de CSS (no se deben modificar)
- _demos_ : Aquí se muestran imágenes de las diversas pantallas del proyecto tanto en la versión desktop y smartphone.
- _demos/apoyo_ : Muestran imágenes de los archivos escritos en Sass.
- _img_ : Imágenes que se usan
- _img/icons_ : Iconos que se usan
- _sass_ : Archivos en formato _Sass_, (aquí se trabajan los estilos)
- _src/componentes_ : Aquí están las carpetas y archivos relacionados a los HTML del proyecto.
  Se ha creado una carpeta por cada tipo de archivo, relacionada a una pantalla, por lo general, y dentro de ella están todos los HTML relacionados a ella.

1. **Login**
   - _login.html_ : Pantalla de acceso
2. **Profile**
   - _profile.html_ : Pantalla de perfil
3. **Boletas**
   - _boletas.html_ : Pantalla inicial de boletas
   - _boletas-descarga.html_ : Pantalla que se muestra en la descarga - es solo mostrada en smartphone
4. **Cancelacion**
   - _cancelacion.html_ : Pantalla para confirmar la cancelación de algún proceso dentro de la aplicación
5. **Filters**
   - _filters.html_ : Pantallas que se muestran los filtros por periodos
6. **Main**
   - _main.html_ : Pantalla principal de la aplicación.
7. **Prestacard**
   - _prestacard.html_ : Pantalla inicial a la aplicación de préstamos
   - _prestacard-cuotas.html_ : Pantalla inicial de la solicitud de préstamo.
   - _prestacard-solicitud.html_ : Determinación de número de cuotas del préstamo.
   - _prestacard-qr.html_ : Informa que se validará la identidad.
   - _prestacard-biometrica.html_ : Toma de fotografía
   - _prestacard-dni.html_ : Captura de la imagen DNI
   - _prestacard-aceptado.html_ : Pantalla de confirmación que se realizó el préstamo.
   - _prestacard-estado.html_ : Pantalla de verificación de estado de deudas

Resulta importante indicar para que sirven los archivos Sass, existe uno por cada HTML(con el mismo nombre, pero con extensión SCSS), pero también se han creado otros de uso público:

- _\_initials.scss_ : Inicializa los estilos.
- _\_menu.scss_ : Diseña el menú que se muestra en varias pantallas.
- _\_mixinsfunc.scss_ : Archivo que contiene mixins y funciones de uso común.
- _\_variables.scss_ : Variables de estilos que se utilizan en todo el proyecto.

---

# PANTALLAS MUESTRA

## LOGIN

![login](/demos/login.png)
![login-smartphone](/demos/login-smart.png)

## PROFILE

![profile](/demos/perfil.png)
![profile-smartphone](/demos/perfil-smart.png)

## MAIN

![main](/demos/principal.png)
![main-smartphone](/demos/principal-smart.png)

## BOLETAS

![boletas](/demos/boletas.png)
![boletas-smartphone](/demos/boletas-smart.png)
![boletas-descarga](/demos/boletas-descarga.png)

## CANCELACION

![cancelación](/demos/cancelacion.png)
![cancelación-smartphone](/demos/cancelacion-smart.png)

## PRESTACARD

![prestacard](/demos/prestacard.png)
![prestacard-smartphone](/demos/prestacard-smart.png)

### CUOTAS

![prestacard-cuotas](/demos/prestacard-cuotas.png)
![prestacard-cuotas-smartphone](/demos/prestacard-cuotas-smart.png)

### SOLICITUD

![prestacard-solicitud](/demos/prestacard-solicitud.png)
![prestacard-solicitud-smartphone](/demos/prestacard-solicitud-smart.png)
![prestacard-estado-smartphone](/demos/prestacard-estado.png)

### IDENTIFICACIÓN

![prestacard-qr](/demos/prestacard-qr.png)
![prestacard-biometrica-smartphone](/demos/prestacard-biometrica.png)
![prestacard-dni-smartphone](/demos/prestacard-dni.png)

Copyright [2022] [Corporación Vega]
