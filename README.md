A partir del codi del projecte de Google LocationUpdates (enllaçat al CV), es demana:

1) Per tal de simplificar el codi s'ha optat per crear un mètode que engloba un bloc de codi que es repetia en dues zones diferents. Es tracta de la funció *requestPermission()* que incorpora codi utilitzat dos cops per la funció *requestPermissions()*: en presionar l'*OK* de l'*SnackBar* i en inicialitzar l'aplicació, i que s'utilitza per fer llençar el diàleg natiu d'Android per demanar permisos de localització.

2) És el mètode que s'executa després de prendre una decisió en el diàleg natiu d'Android en què es demanen permisos. Gestiona quina ha estat la decisió de l'usuari i actua en conseqüència segons els valors d'una *array* de *int*.