# Magnetolvl2
Nivel 2:

URL:https://magneto-343022.uc.r.appspot.com/

Host: GOOGLE CLOUD

Servicio a desarrollar: /mutant


INSTRUCCIONES:

Enviamos a traves de la aplicacion POSTMAN un POST con la url antes nombrada (https://magneto-343022.uc.r.appspot.com/mutant) y un json embebido en el body.

 JSON ejemplo: {"dna": ["ATGCGA","CAGTGC","TTATGT","AGAAGG","CCCCTA","TCACTG"]}    
 Esto deberia dar como respuesta "OK" ya que existe más de 1 secuencia en el adn.
 
 JSON ejemplo: {"dna": ["ATGCGA","CAGTGC","TTATGT","AGAAGG","CCTCTA","TCACTG"]}    
 Esto deberia dar como respuesta "FORBIDDEN" ya que existe SOLO  1 secuencia en el adn.
 
