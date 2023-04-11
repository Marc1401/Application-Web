Nom étudiant : Marc Kouamé

Numéro étudiant : 300161315

Le projet concerne une application web sur la gestion des rendez-vous (appointments) dans un hopital. Il est inspiré d'une application trouvée sur le site campcodes.com 

Logiciels requis : 
- PHP
- Mysql
- XAMPP Control: je travaille sur localhost: 3307

- Sur XAMPP il faut demarrer APACHE et MySql 
![image](https://user-images.githubusercontent.com/91161821/231262248-4060bcb4-7bd6-45c6-ab9c-4a47fe35a393.png)


        1ere etape : 
    Télécharger le folder zip HospitalManagementSystem . 
    Une fois téléchargée, copiez (copy) le.
    
    ![image](https://user-images.githubusercontent.com/91161821/231257045-e97bd41a-dad4-48ea-82dd-c6eb20f84840.png)
)
        
        2eme etape
    Dans File Explorer, allez à This PC -> Windows C -> xampp -> htdocs. Une fois dans htdocs collez(paste) le folder. 
    ![image](https://user-images.githubusercontent.com/91161821/231257392-d86902ab-041c-4258-be11-7784f97c6d8e.png)




        3e etape
    - Ensuite sur un navigateur internet(browser), connecter vous à PHPMyAdmin avec le lien suivant : http://localhost/phpmyadmin
    
      
    - Puis creer une nouvelle base de données en cliquant sur New. 
    ![image](https://user-images.githubusercontent.com/91161821/231257937-84db8ecb-1b83-4a78-9a77-7cb609827a73.png)


    - Nommez la base de données "hms"
    ![image](https://user-images.githubusercontent.com/91161821/231258132-2e4803d5-2e29-459f-a981-856830e1c228.png)
                                

    - Cliquez sur l'onglet "import" et rechercher dans le folder Hospital Management SQL file -> hms.sql et importer ce fichier. 
    
    ![image](https://user-images.githubusercontent.com/91161821/231258357-0989dbde-69e4-48ee-b33f-d230fa3a144e.png)

    

        4e etape
    Vous pouvez finalement vous connecter à l'application avec le lien suivant : http://localhost/hospitalmanagementsystem/HospitalManagementSystem/hospital/

    Section des comptes déjà créés

    For admin : admin/Test@12345
    
    For Patient: test@gmail.com/Test@123
    
    For Doctor: test@demo.com/Test@123


        PRESENTAION DE L'APPLICATION
    
    ADMIN SIDE 
    
    
    L'administrateur a acces au contenu de toute la base de donnees, c'est a dire qu'il gerer les docteurs, les patients, les differents appointments.
    
    
    ![image](https://user-images.githubusercontent.com/91161821/231260127-b763a988-5103-4b4b-9b84-993aa3ae8488.png)
    
    
    
    DOCTOR SIDE 
    
    Le docteur peut gerer(les voir) ses appointements et son profil
    ![image](https://user-images.githubusercontent.com/91161821/231260999-5abcc973-574f-4ade-820e-14425e6a9a9e.png)
    


    PATIENTS SIDE
    
    Les patients peuvent bien sur acceder a leurs profils, visualiser et prendre des Rendez vous 
    
    ![image](https://user-images.githubusercontent.com/91161821/231261996-9ef6fb20-86ea-46a5-994d-137881744cdc.png)

    
    
    
