# Punt restauració 


Tenir un punt de restauració a Ubuntu és important per diverses raons:

Recuperació de dades: En cas de fallades del sistema, errors de programari o canvis que causin problemes, els punts de restauració permeten recuperar l'estat anterior del sistema.

Proves de programari: Si instal·les nous programes o realitzes canvis en la configuració, un punt de restauració et permet desfer aquests canvis fàcilment si no funcionen com esperaves.

Seguretat: Ajuda a mantenir el sistema estable i segur, ja que pots revertir canvis que podrien comprometre el rendiment o la seguretat del sistema.

Estalvi de temps: Si alguna cosa va malament, pots evitar el procés llarg de reinstal·lar el sistema operatiu o reconfigurar les aplicacions, estalviant temps i esforç.

A Ubuntu podem utilitzar el Timeshift per recuperar arxius perduta fent una instantanea.

 ![a](/img/time.avif)

 
 
 
 Per poder fer la prova primer he creat una carpeta amb un arxiu.

 ![a](/img/PROVE.png)


 Ara instal·lem  el timeshift amb apt install.

 ![a](/img/timeshift.png)

Al iniciarlo apareixera el tipo d'instantanea que volem fer elegire Rsync ja que volem fer una prova d'una copia d'un arxiu.

![a](/img/instantanea.png)

Seguirem i ara és creara.
  
  ![a](/img/proces.png)

Ara ens demana que seleccionem de quina partició volem fer la copia he seleccionat la sda1 que és el meu HOME on tinc els fitxers i la capeta prova.

  ![a](/img/part.png)


 Si li posem a continuar ens apareixera l'apartat de la configuració on podem triar quan fer l'instantanea automàticament, mensualment, semanalment, a diari, cada hora o al arrancar.
 
  ![a](/img/config.png)

Ara ens demana quina archius de la partició volem guardar he seleccionat els del root i els arxius que tinc al home.
 
 ![a](/img/zeb.png)

Un cop fe aiò creare la instantanea.

 ![a](/img/crear.png)
 
 ![a](/img/dos.png)
