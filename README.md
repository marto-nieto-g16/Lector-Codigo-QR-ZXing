Los Código QR, Han Estado de Moda Últimamente,
Este es una Mejora Al Código Desarrollado En Este Video: 
https://www.youtube.com/watch?v=exNy01rBApc&t=3s

La librería ZXing, desarrollada por Google, nos permite tomar una cadena de texto, codificarla como una matriz de datos la cual luego se puede convertir a un código QR con el cual podemos generar una imagen en el formato que necesitemos.
El uso de la librería es muy sencillo el cual consiste de los siguientes pasos:

    Crear un objeto QRCodeWriter.
    Crear una cadena de texto con los datos que deseamos poner en el QR.
    Tener a la mano el ancho y altura del código QR que deseamos crear
    Usar el método encode del objeto QRCodeWriter para crear la matriz de datos del QR, se le pasan de argumentos los datos, el ancho y altura que deseamos ver en el QR
    Crear un objeto BufferedImage del mismo exacto tamaño que el código QR.
    Yendo elemento por elemento de la matriz de datos convertirlo a una imagen BufferedImage.
    Usar ese objeto BufferedImage ya sea para mostrar el Código QR en pantalla, imprimirlo o guardarlo.

Demo: https://youtu.be/7pfs6h6lHfM
