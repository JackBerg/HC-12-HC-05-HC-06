


http://www.thebackshed.com/forum/forum_posts.asp?TID=10247&PN=1



Vous aurez besoin d'un adaptateur USB vers s�rie tel que le module CP2102 ou une unit� MicroBridge bas�e sur 1455.

1) Connectez le module RXD (entr�e) du module HC12 � la sortie TXD (sortie) de l�adaptateur USB / s�rie.
2) Connectez le TXD (sortie) du module HC12 au connecteur RXD (entr�e) de l�adaptateur USB / s�rie.
3) Connectez la terre du HC12 � la terre de l�adaptateur USB / s�rie.
4) Connecter le SET de HC12 � la terre.
5) Connectez le VCC du HC12 � la sortie 5v de l�adaptateur USB / s�rie.
6) Lancez le programmateur HC12 de Rob et connectez-vous au port COM de l'adaptateur USB / s�rie.

Vous devriez maintenant �tre capable de lire les param�tres actuels et de modifier ce que vous voulez, puis de r��crire les nouveaux param�tres dans le module. Une fois termin�, d�branchez les c�bles du HC12. Lorsque vous reconnectez l'alimentation, le HC12 devrait utiliser les nouveaux param�tres.