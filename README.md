# ccd-projekt-ani
Testprojekt, um Github und die Versionskontrolle auszuprobieren im Rahmen des BHT Kurses Softwaretechnik.

![Screenshot 2025-06-01 124108](https://github.com/user-attachments/assets/9db349db-40e3-486f-a64f-36cac3937a94)

![Screenshot 2025-06-01 124637](https://github.com/user-attachments/assets/70e1f1cf-7ae9-4d4c-b97c-517bb97f6b66)

![Screenshot 2025-06-01 125011](https://github.com/user-attachments/assets/a6e0d4b7-fd5b-4f5b-aaf8-45610659dc1c)

![Screenshot 2025-06-01 125510](https://github.com/user-attachments/assets/fcb95608-7c47-4e37-877d-95b690fe7e44)

![Screenshot 2025-06-01 130149](https://github.com/user-attachments/assets/01943818-22e3-4877-87ef-f42790325880)

![Screenshot 2025-06-01 131135](https://github.com/user-attachments/assets/14f9a4fe-d7a3-4217-885d-fd843e537917)
[Befehl Commit angewandt. Path zum Projekt nicht mit Laptop User Name anian sondern mit Github User Name matsunik: https://github.com/matsunik/ccd-projekt-ani/edit/main/README.md]

ccd-projekt-ani/

├── README.md

├── fakten.md

└── tiere/

    ├── hund.txt
    
    ├── katze.txt
    
    ├── elefant.txt
    
    └── giraffe.txt

    
![Screenshot 2025-06-01 165225](https://github.com/user-attachments/assets/20eea0c9-e3e7-4183-9a0c-a7ada46247a0)

[Mit git diff Textdatei ändern, Text löschen und Text hinzufügen]

###  Konflikt beim Push gelöst
#### Die Textdateiänderung in giraffe war noch nicht committed. Daher der Konflikt zwischen dem Stand im github repositpry und der lokalen Speicherung. 

```powershell
$ git status
Changes not staged for commit:
  modified:   tiere/giraffe.txt

$ git add .
$ git commit -m "Lokale Änderungen vor Pull gesichert"
$ git pull --rebase
$ git push´´´

![Screenshot 2025-06-01 165225](https://github.com/user-attachments/assets/0acc05f3-a769-444e-b6e9-2c673a8e3a4f)

![Screenshot 2025-06-01 170151](https://github.com/user-attachments/assets/328c242c-b96b-4602-b245-878049e6fea9)
