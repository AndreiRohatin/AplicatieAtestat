# AplicatieAtestat
# FirstPersonalProject

AplicatieAtestat este o mesagerie open source care foloseste o baza de date de tipul NoSQL (firebase) oferind o criptare a datelor utilizatorilor prin intermediul criptarii XOR.


Criptarea XOR implementata foloseste chei de criptare de lungime variabila (minim 10 caractere), avand caracterele din interiorul acesteia diferite pentru fiecare utilizator.
Problema actuala a criptarii implementate este ca nu este dinamica pentru fiecare mesaj in parte si poate sa fie aflata prin folosirea operatii xor intre 2 mesaje trimise de 
acelasi utilizator catre aceiasi persoana. 

Am ales criptarea XOR deoarece ofera o criptare destul de sigura care la prima vedere nu este atat de usor de descifrat datorita operatiilor pe biti efectuate de catre operatia 
XOR.
