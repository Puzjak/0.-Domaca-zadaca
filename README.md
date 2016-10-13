#JMBAG
0036492904

#Pitanje 1
U mapi se stvori ClassLibrary1.dll
Ukoliko ga obrisem javit ce mi error da ne moze ucitati file ili assembly. 
To je jer u dll fileu ima referencu na novu klasu u kojoj se nalazi metoda koja je potrebna da se program izvrsi do kraja. 
Da bi program radio potrebni su samo .exe i .dll datoteke.

#Pitanje 2
Program ispise stari tekst jer vuce referencu iz .dll datoteke koja nije azurirana posto ClassLibrary1 projekt nije preveden.

#Pitanje 3
Pero: Hello World

#Pitanje 4
.dll file se kopirao u Bin\Debug datoteku

#Pitanje 5
Ako se obrise originalna lokacija sa koje je taj .dll kopiran aplikacija ce i dalje raditi posto nova putanja u referenci ide do Bin\Debug foldera.

#Pitanje 6
Projekt se uspio buildati i u packages se ponovo pojavio NodaTime.1.3.2 folder.
