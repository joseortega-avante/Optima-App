# Versión 1.0.1

**Lanzada el 18 de octubre de 2024**

## Mejoras y correcciones:

### Corrección de Acceso de Usuarios
- Se ha solucionado un problema en el proceso de autenticación de usuarios, mejorando la estabilidad y fiabilidad del login.

### Restricción en el botón "Back" de Android
- Ahora, una vez que los usuarios han iniciado sesión, ya no es posible regresar a la pantalla de login utilizando el botón "Back" del dispositivo Android, mejorando la seguridad de la sesión.

### Último usuario guardado en el login
- Se ha implementado una funcionalidad que guarda el último usuario que inició sesión. Cuando la aplicación se reinicia, este usuario se muestra automáticamente en el campo de usuario para facilitar el acceso.

### Petición de número de tienda
- Si el nombre de usuario no comienza con "osuc", se solicita al usuario que ingrese un número de tienda al iniciar sesión, lo que permite un manejo más personalizado de las cuentas.

### Enfoque manual en la cámara
- Se ha añadido la funcionalidad de enfoque manual al hacer clic en la pantalla mientras se utiliza la cámara para escanear códigos de barras. Esto mejora la precisión del escaneo en condiciones de poca iluminación o con códigos pequeños.

### Optimización del Almacenamiento
- Se han optimizado los recursos de la aplicacion, de modo que en vez de pesar 250 MB ahora pesa 120MB.

### Compatibilidad
- Ahora es compatible con Android 9.0 y versiones superiores.

## Requerimientos Mínimos

<table align="center">
    <tbody>
        <tr>
            <td style="font-weight: bold" align="center">Sistema Operativo</td>
            <td align="center">Android 9.0 o Superior.</td>
        </tr>          
        <tr>
            <td style="font-weight: bold" align="center">Hardware</td>
            <td align="center">Camara Funcional para escanear codigos de barras. <br> Conexión a internet (Wi-fi o Datos Moviles).</td>
        </tr>
                <tr>
            <td style="font-weight: bold" align="center">Almacenamiento</td>
            <td align="center">Al menos 150 MB de espacio libre para la instalación.</td>
        </tr>  
                <tr>
            <td style="font-weight: bold" align="center">Permisos</td>
            <td align="center">Acceso a la cámara para escanear codigos de barras. <br> Acceso a la red (Wi-Fi o Datos Móviles) para autenticación y consultas.</td>
        </tr>  
    </tbody>
</table>