# TP2-CienciaDeDatos-FIUBA
Su tarea es crear un modelo que pueda predecir si una dirección IP está asociada con un servicio de VPN o Proxy en el marco de una competencia de Kaggle. Los alumnos deberán participar en la competencia de Kaggle: Binary Classification of VPN Proxy IP Address.

Los modelos serán evaluados en función de su desempeño en el conjunto de pruebas privadas proporcionado por la plataforma. Si bien la participacion en la competencia es central, el resultado de ella no es determinante en la nota. Se debe prestar atención al criterio de corrección y a las consignas de esta pagina ya que son las que usaremos. En particular, el score que vamos a utilizar para validar nosotros es el mismo que el que usa la competencia: F1-Score.

Dataset a usar
El conjunto de datos proporcionado consiste en una muestra aleatoria de ataques reportados por el software de CrowdSec. Ambos sets (el de training y el de test), estan disponibles en la pagina de la competencia.

Cada entrada representa un ataque, y consta de algunas características del mismo (hora del ataque, tipo, etc) segun lo inferido por el sistemas de detección de amenazas. Debido a la naturaleza confidencial de los datos, las direcciones IP se encuentran anonimizadas en un ID compartido entre todos los archivos. Tengan en cuenta que el conjunto de datos está bastante desequilibrado, ya que solo alrededor del 5% de las entradas se identifican como procedentes de VPN o servidores proxy.
