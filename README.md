# Hantering of filer - första uppgiften i github classroom.
Länk till genomgång= https://docs.google.com/presentation/d/1Ol-GrnCoHWU6hLaULL6N63bwcnVf7q9U9fPebd1hOXI/edit?usp=sharing

Öppna filer
f = open("test.txt",'w')  # öppnar filen test.txt i Skriv läge för filen 

f = open("test.txt",'r')  # öppnar filen test.txt i Läs läge för filen

f = open("test.txt",'a')  # öppnar filen test.txt i append läge för filen

f.close() # stänger filen du nyss öppnade 

Öpnna och skriver till en fil 

f=open("test.txt",'w')

f.write("Min första fil\n")

f.write(“Denna fil n\n")

f.write("innehåller tre rader\n"

