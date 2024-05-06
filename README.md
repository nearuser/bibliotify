# bibliotify
script para capturar tu biblioteca de spotify ordenada alfabeticamente y guardarla en un documento docx

##PRIMERO : CLONA ESTE PROYECTO USNADO git clone 

            git clone https://github.com/nearuser/bibliotify.git

##SEGUNDO : ABRE UNA TERMINAL EN LA CARPETA QUE HAS CLONADO y ejecuta el siguiente comando 

            pip install -r requirements.txt
            
(esto instalara los requerimientos de python necesarios para ocupar este script) 

##INSTRUCCIONES DE USO : 

1.- tener python en tu sistema , este script esta desarrollado en python 3.10 por lo que idealmente debes contar con esta version, pues ocupar alguna mas antigua podria generar problemas de compatibilidad. 

2.- disponer de un IDE o editor para poder revisar y modificar el código. 

3.- si quieres usar el programa reber tener un ID_CLIENT y un CLIENT_SECRET para tener acceso a la API de SPOTIFY. Estos los obtienes en dashboard developer       de Spotify
    si por alúun motivo te complica obtener un ID_CLIENT y SECRET ponte en contacto conmigo para que te proporcione uno. 

4.- Una vez tengas las credenciales señaladas anteriormente deber crear un archivo .env en la raíz de proyecto que has clonado. aqui pondras lo siguiente 

    CLIENT_ID='----------------------------'
    CLIENT_SECRET='-------------------------'
    REDIRECT_URI='http://localhost:8888/callback'

  donde en los espacios ocupados por -------- pondras las respectivas credencials entregadas en el dashboard de spotify

5.- Si todo esta en orden , ya podras usar el script ya sea desde una terminal con el comando 'python main.py' o dando play en la esquina superior derecha si      es que usas PyCharm como IDE.

##NOTA : el funcionamineto es sencillo y automatico, cuando ejecutes el script se abrirá una ventana en tu navegador predeterminado (CHROME, FIREFOX, BRAVE etc) . ahi te solicitara inicar sesion en Spotify. Esto es necesario para que el script tenga acceso a tu biblioteca de musica y pueda trabajar. 
si las credenciales de usuario son correctas la ventana se congelará mientras lista toda tu música (queda pendiente trabajar sobre una vista de LOADING ..) 
Una vez se complete el listado veras el mensaje "CONEXIÓN EXITOSA, YA PUEDES CERRAR ESTA VENTANA).
 
En la carpeta donde clinaste este proyecto tendras un archivo .docx llamado "listado_pistas.docx" 

##PROXIMAMENTE MEJORAS VISUALES Y ESTETICAS




