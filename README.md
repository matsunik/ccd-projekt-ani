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

## Fehlerbehebung

![Screenshot 2025-06-01 170151](https://github.com/user-attachments/assets/70ea5e57-5af3-4b9b-a36a-7a0c578d8dee)

![Screenshot 2025-06-01 171558](https://github.com/user-attachments/assets/a0e05b65-8694-455f-a304-0c2d8b4a1d7b)

[tiere.txt entfernen, um nur mit tiere-Ordner zu arbeiten. Konflikt zwischen github und lokalem Speicherstand zuerst beheben.]

###  Konflikt beim Push gelöst
#### Die Textdateiänderung in giraffe war noch nicht committed. Daher der Konflikt zwischen dem Stand im github repositpry und der lokalen Speicherung. 
#### In Powershell mit git status, add, commit, pull --rebase, git push.

![Screenshot 2025-06-01 165225](https://github.com/user-attachments/assets/5099aa8b-eaf7-4132-911a-2213596b81fc)

![Screenshot 2025-06-01 170151](https://github.com/user-attachments/assets/4a9e9a56-8fd2-4019-87ef-adecd6738800)

[Ich bekomme einfach die Screenshots nicht aus dem Codeblock herausgelöst, daher Codezelle gelöscht]

## Branches erstellen und dann mergen

![Screenshot 2025-06-01 175139](https://github.com/user-attachments/assets/02638502-7b2a-45bb-815c-db613c889e68)

![Screenshot 2025-06-01 175600](https://github.com/user-attachments/assets/05097f7e-b385-4fc6-90f2-e844f1256ee4)

![Screenshot 2025-06-01 180103](https://github.com/user-attachments/assets/0c37d576-9f0b-4559-be3b-600e3728c7cf)

## Textdatei Änderungen bei hund.txt und katze.txt nicht sichtbar, weil als Binärdatei erkannt in git. Suche nach Lösung...

## Weitere Fragen entstehen beim Machen

![Screenshot 2025-06-01 181610](https://github.com/user-attachments/assets/f002093e-d058-4660-bf68-34a76da84724)

[kann ich mit einigen Buttons in Github dasselbe erreichen, wie mit Befehlen in Powershell?]

[Ich habe dazu ChatGPT befragt, und erfahren, wann man lokal arbeitet und wann in git]

![Screenshot 2025-06-01 181833](https://github.com/user-attachments/assets/82b63266-9be0-418c-a5d4-44d04f67e950)

## Git-Befehle nachgewiesen bisher
git add tiere/katze.txt
git commit -m "Katze ergänzt"
git rm tiere.txt
git mv tiere/hunde.txt tiere/hund.txt
git pull --rebase
git push
