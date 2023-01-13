


http://www.thebackshed.com/forum/forum_posts.asp?TID=10247&PN=1



Vous aurez besoin d'un adaptateur USB vers série tel que le module CP2102 ou une unité MicroBridge basée sur 1455.

1) Connectez le module RXD (entrée) du module HC12 à la sortie TXD (sortie) de l’adaptateur USB / série.
2) Connectez le TXD (sortie) du module HC12 au connecteur RXD (entrée) de l’adaptateur USB / série.
3) Connectez la terre du HC12 à la terre de l’adaptateur USB / série.
4) Connecter le SET de HC12 à la terre.
5) Connectez le VCC du HC12 à la sortie 5v de l’adaptateur USB / série.
6) Lancez le programmateur HC12 de Rob et connectez-vous au port COM de l'adaptateur USB / série.

Vous devriez maintenant être capable de lire les paramètres actuels et de modifier ce que vous voulez, puis de réécrire les nouveaux paramètres dans le module. Une fois terminé, débranchez les câbles du HC12. Lorsque vous reconnectez l'alimentation, le HC12 devrait utiliser les nouveaux paramètres.