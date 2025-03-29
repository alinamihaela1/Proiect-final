# Proiect-final
Acest proiect este destinat testării API-urilor folosind Postman. Scopul principal este verificarea funcționalităților de autentificare, gestionare a utilizatorilor și manipulare a notițelor într-o aplicație, dar și folosirea cunoștințelor dobândite prin cursul de testare și de a le pune în practică. 

Aplicația testată : https://practice.expandtesting.com/#google_vignette

Instrumente folosite :Postman

Metodele HTTP acceptate de acest API sunt: GET, POST, PUT, PATCH și DELETE. De exemplu, am folosit GET pentru  a obține date sau pentru a verifica starea autentificării, POST- pentru  a trimite informații  (cum ar fi numele de utilizator și parola) către server, pentru a autentifica utilizatorul, 



Teste efectuate

1. Am folosit "health check" în Postman pentru a verifica dacă o aplicație este activă și funcționează corect.

![Screenshot 2025-03-28 115225](https://github.com/user-attachments/assets/72166e5a-ca1f-47d8-9e71-648337edac50)

Apoi, am scris un test si răspunsul a fost FAILED.
Codul testului verifică corect codul de status al răspunsului.
API-ul returnează un cod de status 200 OK, așa cum se așteaptă testul, însă Postman indică faptul că testul a eșuat, în ciuda faptului că toatele datele sunt corecte.

![Screenshot 2025-03-28 115412](https://github.com/user-attachments/assets/474d6996-1609-4926-b9ad-de4646f8bd90)












2.  Înregistrare utilizator

   
   Metoda HTTP pentru solicitare: POST

   
   Am adăugat un utilizator nou, prin secțiunea Body-raw din Postman folosind documentația API.










3. Autentificare utilizator
   
   Metoda HTTP pentru solicitare: POST
![Screenshot 2025-03-27 185108](https://github.com/user-attachments/assets/3533fc98-f393-4f1a-a2f1-d0a9ce381850)

Teste JavaScript
![Screenshot 2025-03-27 185740](https://github.com/user-attachments/assets/aa75148e-e3e8-4ab5-b0c4-64192b127d76)
![Screenshot 2025-03-27 185820](https://github.com/user-attachments/assets/f67c24b7-739c-4e93-a3c9-7485a2daffce)











4. Profil ultilizator

   Am trimis o cerere GET, pentru a prealua informații despre utilizator.


   Metoda HTTP pentru solicitare: GET
![Screenshot 2025-03-29 193445](https://github.com/user-attachments/assets/ca2b228f-4a89-4052-99e7-513a3240b6d9)


Teste JavaScript

![Screenshot 2025-03-29 193639](https://github.com/user-attachments/assets/03b22084-437c-4fb3-aaa8-d2df823c3385)

![Screenshot 2025-03-29 193743](https://github.com/user-attachments/assets/839b0b53-0b2b-4c03-9498-1a3a8ba2c6f8)

![Screenshot 2025-03-29 193801](https://github.com/user-attachments/assets/82128877-20f2-4792-b789-d7c748895dec)







  5. Actualizare profil
  
      
Metoda HTTP pentru solicitare: PATCH

   ![Screenshot 2025-03-27 190452](https://github.com/user-attachments/assets/8002ea65-0f1c-4a48-9e41-938a6b54bb6b)


Teste JavaScript
![Screenshot 2025-03-27 190650](https://github.com/user-attachments/assets/5c454d4f-03e4-4746-8469-103ae47ad828)
![Screenshot 2025-03-27 190710](https://github.com/user-attachments/assets/0d2b5280-19ac-4285-b35e-d5c925e63532)
![Screenshot 2025-03-27 190730](https://github.com/user-attachments/assets/4aba954d-e102-4fa4-9c44-4390065a5f1c)













6. Creare notiță
   
   Metoda HTTP pentru solicitare: POST
![Screenshot 2025-03-28 140028](https://github.com/user-attachments/assets/28ab58a0-ebce-4a91-87cd-1b1d6110d362)

Teste JavaScript
![Screenshot 2025-03-28 140226](https://github.com/user-attachments/assets/f17675d2-9546-43ff-8c50-9dd956f96f17)
![Screenshot 2025-03-28 140311](https://github.com/user-attachments/assets/a5187311-8226-455a-b743-96a861eb1a84)
![Screenshot 2025-03-28 140327](https://github.com/user-attachments/assets/6e98591a-bc01-4450-a99a-811a88eda331)







-. 



















   

