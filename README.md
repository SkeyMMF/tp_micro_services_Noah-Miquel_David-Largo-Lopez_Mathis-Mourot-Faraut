***Service Evenement***  
Ce projet correspond au micro-service correspondant à la gestion d'évènement.  

Il propose quatre routes API qui sont les suivantes:   
GET /                             --> renvoie la liste des évènements  
GET /<id-évènement>/isncrits      --> renvoie la liste des inscrits a un évènement  
POST /                            --> créer un évènement  
POST /<id-évènement>/inscriptions --> inscris un joueur a un évènement   


Pour utiliser les routes POST il est néccessaire d'avoir un Token jwt et pour la création, un rôle d'admin est necessaire    
Lien vers le github : https://github.com/SkeyMMF/tp_micro_services_Noah-Miquel_David-Largo-Lopez_Mathis-Mourot-Faraut
