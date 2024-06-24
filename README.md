# Testare-Python
Informatii, linkuri, documentatie, etc.


- https://www.python.org/downloads/ -----Instalare Python

- https://realpython.com/python-idle/  ----- Tutorial Python + cum se face un calculator 

- https://www.freecodecamp.org/news/command-line-commands-cli-tutorial/ ( tutorial Terminal/linie de comanda)
- https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/  ( cum sa faci un add,commit si push la un repo)
- https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands   (comenzile pentru linia de comanda)

- pentru intreruperea unui program care se executa, se apasa ^CTRL+C

- Daca sunt modificari nesalvate, apare ,,*,, la denumirea fisierului.

- Pentru completarea automata a numelui funcțiilor și claselor, se apasa tasta Tab după o secvență de text.

- Ce este append? ex: 
fructe = ['mere', 'pere', 'banane']
fructe.append('cireșe')
print(fructe)
Cu aceasta functie, se adauga la sfarsitul listei cuvantul ,,cirese,, , fara a mai fi nevoie sa cream o noua lista.
Se va afisa: mere,pere,banane,cirese

- Se pot folosi pt print(" "), sau print(' '), e acelasi lucru.

- Pentru afisare print, se poate scrie print("Hello")/print('Hello'), sau doar Hello - e acelasi lucru si fara sa scriem print.

- Daca x=5
print(x)
se afiseaza 5, Dar daca dam din bara de control RESTART, se sterge tot ce era inainte, deci daca vom rescrie print(x), ne va da eroare, deoarece nu este predefinit.

- while True:
    print(Hello)-- se va afisa la infinit cuv. ,,hello".

    user_input= input("What is your name?")
    if user_input =="Python":
  print("Welcome to IDLE")
    else:
    print("Welcome to Python")


- commit -înseamnă să salvezi starea curentă a proiectului  în istoricul Git. 
Pentru a crea o clona in git: se deschide git bash, se scrie pwd(pentru afisarea directorului local)
    Pasul 1: cd Desktop(se alege directorul ) (cd -pentru a intra in director)
    Pasul 2: se codiaza codul URL(din git-la code) git clone (..url...)
    Pasul 3: cd Testare-Python( se denumeste subdirectorul la fel ca si repo din Git)
    Pasul 4: ls -a (pentru a lista toate fisierele din subdirector)
    Pasul 5: deschidem README.md (din folderul ce s-a format) intr-un editor de text, ex.notes si facem modificari. apoi il salvam
    Pasul 6: git status (pentru a vedea in ce branch ne aflam. ex main)
    Pasul 7: git add --all (pentru a adauga toate fisierele din subdirector)
             sau git add README.md( pentru a adauga doar fisierul modificat readme.md)
    Pasul 8: git commit -m "Mesaj sugestiv pentru care se face commit-ul"
    Pasul 9: git push ( pentru a trimite totul in Git)



