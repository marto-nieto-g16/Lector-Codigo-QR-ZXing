
La librería ZXing, desarrollada por Google, nos permite tomar una cadena de texto, codificarla como una matriz de datos la cual luego se puede convertir a un código QR con el cual podemos generar una imagen en el formato que necesitemos.
El uso de la librería es muy sencillo el cual consiste de los siguientes pasos:
1. Crear un objeto QRCodeWriter.
2. Crear una cadena de texto con los datos que deseamos poner en el QR.
3. Tener a la mano el ancho y altura del código QR que deseamos crear
4. Usar el método encode del objeto QRCodeWriter para crear la matriz de datos del QR, se le pasan de argumentos los datos, el ancho y altura que deseamos ver en el QR
5. Crear un objeto BufferedImage del mismo exacto tamaño que el código QR.
6.Usar ese objeto BufferedImage ya sea para mostrar el Código QR en pantalla, imprimirlo o guardarlo.

<img src="https://github.com/marto-nieto-g16/Lector-Codigo-QR-ZXing/blob/master1/QR%20En%20Java.png" />
Demo: https://youtu.be/lAaoVfG_EhM

<img src="https://github.com/marto-nieto-g16/Lector-Codigo-QR-ZXing/blob/master1/QR%20Naruto%20(1).png" />

