# QRCreator
Este código en Python utiliza la biblioteca Pillow (PIL) y el módulo qrcode para generar un código QR.
1. Importar Módulos
- Se importa la clase 'Image' de la biblioteca Pillow (PIL) para trabajar con imágenes.
- Se importa el módulo 'qrcode' para generar códigos QR.

2. Configuración del obejto QRCode
- Se crea un objeto 'QRCode' con ciertos parámetros de configuración.
- La versión del código QR es 1.
- El nivel de corrección de errores se establece en 'ERROR_CORRECT_L' (baja corrección de errores).
- 'box_size' define el tamaño de cada "celda" en el código QR.
- 'border' establece el ancho del borde del código QR.

3. Añadir datos al código QR
- Se añaden los datos que se codificarán en el código QR. En este caso, es la ruta "C:\Users\DELL\Desktop\Emerson".

4. Generar código QR
- Se genera el código QR, y 'fit=True' indica que se ajuste automáticamente al tamaño de los datos.

5. Crea imagen de Código QR
- Se crea una imagen del código QR con fondo blanco y celdas en negro.

6. Guardar la imagen
- La imagen del código QR se guarda en un archivo llamado "output.png".
