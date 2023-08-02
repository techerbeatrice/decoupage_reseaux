# Découpage réseaux de manière asymétrique
Le Pôle Informatique (6 bureaux, environ 50 équipements au total)-------> 2⁶-2 = 64-2 = **62 adresses hosts disponibles**    
Le Pôle Administratif (4 bureaux, environ 20 équipements au total)-----> 2⁵-2 = 32-2 = **30 adresses hosts disponibles**          
Le Pôle Technicien (4 bureaux, environ 15 équipements au total)---------> 2⁵-2 = 32-2 = **30 adresses hosts disponibles**   
Le Pôle Développement (6 bureaux, environ 12 équipements au total)-----> 2⁴-2 = 16-2 = **14 adresses hosts disponibles**           

|Réseau : 172.16.1.0/24|Adresse réseau|Adresse de broadcast|Adresse de début de plage|Adresse de fin de plage|
|:---|:----|:---|:---|:----|
|**Le Pôle Informatique (6 bureaux, environ 50 équipements au total)**    | 172.16.1.0/26   | 172.16.1.63/26 | 172.16.1.1    | 172.16.1.62   |
| **Le Pôle Administratif (4 bureaux, environ 20 équipements au total)**    | 172.16.1.64/27 | 172.16.1.95/27 | 172.16.1.65    | 172.16.1.94 |
| **Le Pôle Technicien (4 bureaux, environ 15 équipements au total)**    | 172.16.1.96/27 | 172.16.1.127/27 | 172.16.1.97   | 172.16.1.126 |
| **Le Pôle Développement (6 bureaux, environ 12 équipements au total)**    | 172.16.1.128/28 | 172.16.1.143/28 | 172.16.1.129    | 172.16.1.142 |

# Découpage réseaux de manière symétrique   
2⁶-2 = 64-2 = **62 adresses hosts disponibles** dans tous les pôles     

|Réseau : 172.16.1.0/24|Adresse réseau|Adresse de broadcast|Adresse de début de plage|Adresse de fin de plage|
|:---|:----|:---|:---|:----|
|**Le Pôle Informatique**| 172.16.1.0/26| 172.16.1.63/26 | 172.16.1.1| 172.16.1.62|
|**Le Pôle Administratif**| 172.16.1.64/26| 172.16.1.127/26| 172.16.1.65| 172.16.1.126|
|**Le Pôle Technicien**| 172.16.1.128/26 | 172.16.1.191/26 | 172.16.1.129   | 172.16.1.190 |
|**Le Pôle Développement**| 172.16.1.192/26 | 172.16.1.255/26 | 172.16.1.193    | 172.16.1.254|
