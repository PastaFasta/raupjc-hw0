# raupjc-hw0
Zero homework on C# course.

#Pitanje 1.
Nakon što sam dodao class library kao referencu, u mapi Bin/Debug stvorene su još dvije datoteke (ClassLibrary1.dll i ClassLibrary.pdb)
Nakon što sam maknuo .dll datoteku i pokrenuo .exe program se srušio i bacio System.IO.FileNotFoundException iznimku zato što ne može pronaći međukod metode PrintHelloWorld koja se nalazi u našoj biblioteci koja nije dio .NET biblioteka.
Poslat ću .exe i .dll datoteke.

#Pitanje 2.
Program je pokazao novi string zato što je prije izvođenja rebuildao ClassLibrary1.

#Pitanje 3.
Build proces je restorao NuGet pakete i normalno buildao aplikaciju. U packages direktoriju se ponovno stvorio NodaTime direktorij.
