# 01-03-02-gyak
## StudentProject
Iskolába járó diák elvégez egy osztályt.
A fejlesztő csapat munkája után elkészült az osztály UML diagramja. Ön azt a feladatot kapta, hogy fejlessze ki az osztályt!     

![alt text](https://github.com/csarp-dotnet-core-oop-feladatok/01-03-02-gyak/blob/main/StudentClass.png "UML diagram")   

Munkája ellenőrzéseként használja a következő kódot:   
```
Student studentJhon = new Student("Jeles János", 3);
studentJhon.ToConsole();
studentJhon.CompletesStudentTheClass();
studentJhon.ToConsole();
studentJhon.CompletesStudentTheClass();
studentJhon.ToConsole();

Student studentPeter = new Student("Példás Péter", 7);
studentPeter.ToConsole();
studentPeter.CompletesStudentTheClass();
studentPeter.ToConsole();
studentPeter.CompletesStudentTheClass();
studentPeter.ToConsole();

```
A kód kimenete a következő kell legyen:     
Jeles János 3. osztályos tanuló. Alsó tagozatra jár.    
Jeles János 4. osztályos tanuló. Alsó tagozatra jár.    
Jeles János 5. osztályos tanuló. Felső tagozatra jár.     
Példás Péter 7. osztályos tanuló. Felső tagozatra jár.    
Példás Péter 8. osztályos tanuló. Felső tagozatra jár.    
Példás Péter 9. osztályos tanuló. Készül az érettségire.    
