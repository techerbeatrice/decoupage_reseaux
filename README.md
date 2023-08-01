# Découpage réseaux
Le Pôle informatique (6 bureaux, environ 50 équipements au total)-------> 2⁶-2 = 64-2 = 62 adresses hosts disponibles     
Le Pôle développement (6 bureaux, environ 12 équipements au total)-----> 2⁴-2 = 16-2 = 14 adresses hosts disponibles      
Le Pôle Administratif (4 bureaux, environ 20 équipements au total)------> 2⁵-2 = 32-2 = 30 adresses hosts disponibles      
Le Pôle Technicien (4 bureaux, environ 15 équipements au total)---------> 2⁵-2 = 32-2 = 30 adresses hosts disponibles       

| Réseau : 172.16.1.0/24  | Adresse réseau | Adresse de broadcast |Adresse de début de plage  | Adresse de fin de plage |
| :---    |  :----:  |    ---: | :---    |  :----:  |
| Le Pôle Informatique (6 bureaux, environ 50 équipements au total)    | 172.16.1.0/26   | 172.16.1.63/26 | 172.16.1.1    | 172.16.1.62   |
| Le Pôle Développement (6 bureaux, environ 12 équipements au total)    | 172.16.1.64/28 | 172.16.1.79/28 | 172.16.1.65    | 172.16.1.78 |
| Le Pôle Administratif (4 bureaux, environ 20 équipements au total)    | 172.16.1.80/27 | 172.16.1.111/27 | 172.16.1.81    | 172.16.1.110 |
| Le Pôle Technicien (4 bureaux, environ 15 équipements au total)    | 172.16.1.112/27 | 172.16.1.143/27 | 172.16.1.113    | 172.16.1.142 |
