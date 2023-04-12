# ESTATIC-ADA



#Virtual Routes
const express = require('express');
const app = express();

// Definir la ruta virtual para servir archivos estáticos
app.use('/static', express.static('public'));

// Iniciar el servidor
app.listen(3000, () => {
  console.log('Servidor iniciado en el puerto 3000');
});



#Estatic a nivel de aplicacion
// importando express
const express = require('express');

//usando express
const app = express();

app.use(express.static('public'));

app.listen(3000, () => {
  console.log('La aplicación está escuchando en el puerto 3000');
});


Recuerden tener la carpeta public en el servidor
