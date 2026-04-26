# Active Directory Domain Services - Les OU

## Domaine utilisé
- Domaine : `wilders.lan`
- Utilisateur créé : `Wilder1`
- Client joint au domaine : `PCDEYANN`

---

## 1. OU utilisateurs
L’unité d’organisation **Wilders_students** contient bien le compte utilisateur **Wilder1**.

<img width="461" height="292" alt="51d09667-f383-4414-9acc-af39631bd84c" src="https://github.com/user-attachments/assets/c6df8ebb-32e8-4707-af65-bcb7f3abe9a2" />

---

## 2. OU ordinateurs
L’unité d’organisation **Wilder_Computers** contient bien le poste client **PCDEYANN**.



---

## 3. Groupe utilisateurs
Le groupe **GrpUsersStudents** contient bien l’utilisateur **Wilder1** dans ses membres.



---

## 4. Groupe ordinateurs
Le groupe **GrpComputersStudents** contient bien l’ordinateur **PCDEYANN** dans ses membres.


---

## 5. Vérification côté client
La commande `whoami` montre que la session ouverte sur le client est bien celle du compte domaine **wilders\wilder1**.

<img width="379" height="175" alt="df9b01a8-528d-4967-9a71-8296ec6070e3" src="https://github.com/user-attachments/assets/7201a1ee-5355-4424-afde-d71152684c34" />
<img width="370" height="173" alt="77da97b1-7a13-46d2-9777-6f5b84a93a02" src="https://github.com/user-attachments/assets/b98bc7ff-826e-473a-870e-acc90ea1d406" />
<img width="270" height="123" alt="1958cf3d-d75f-4419-af1e-bfdbfe9fe7a9" src="https://github.com/user-attachments/assets/544b8f76-6694-4b6b-b098-67df52b44fda" />
<img width="530" height="348" alt="df786f27-e4bb-45fd-bb3c-cf93b5ea6b2f" src="https://github.com/user-attachments/assets/864a1074-b490-4f8f-8724-c06da94f385d" />

