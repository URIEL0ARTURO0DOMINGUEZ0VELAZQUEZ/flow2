# flow2
pasos a seguir
#comencemos 
primero antes que todo tenemos que arrancar los contenedores o mas bien se puede arrancar el contenedor que se vamos a utilizar
con el comando **docker start [id_del_contenedor_de_node_red]**
para pode consultar tu id del contenedor es con el sig. comando **docker ps -a**

ya que esten arrancados ahora podemos entra con nuestro tcp en  nuestro buscador de la sig manera **localhost:1880**
y hacer las modificaciones que queramos en *Node-RED*

luego al estar en nuestro navegador en node-RED Inserta un Nodo function de la paleta de nodos y conecta su entrada a la salida de inject y su salida a la entrada de debug.
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/flow2/assets/136390705/4e7f04e3-8bb3-4013-8a57-cfa5a96f670c)

