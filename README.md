# BazaDeDate-Magazin

# Descrierea modelului real
Baza de date este facuta pentru a fi utilizată pentru a ajuta cumparatorul sa afle informatii despre produsul pe care il cumpara, de exemplu de cine este facut si informatii despre omul care a facut produsul pe care doreste sa si-l cumpere.
Entitatea Client stocheaza informatii despre un client cum ar fi numele sau,prenumele,numarul de telefon si alte informatii personale.Entitatea Comanda contine ID-ul clientului,Data in care a fost livrata comanda si date in care aceasta ajunge.Aceasta este legata printr-o tabela asociativa de Produs care are 3 subentitati AlbumMuzical,Carte si Film care reprezinta ce doreste clientul sa cumpere.Ele sunt ajutate de catre atribute ca sa  descrie genul continutului si pretul cu care pot fi cumparate, dar si de alte entitati ca sa  spuna detalii despre omul care a facut produsele.
	Alta entitate care este folosita in baza de date este Magazin care este in relatie cu Produs, iar in fiecare magazin pot sa lucreze unul sau mai multi angajati.Entitatea Angajat contine informatii unice despre un angajat cum ar fi adresa de email,orasul in care locuieste, iar entitatea Job ne spune despre functia pe care o detine fiecare angajat si orele pe saptamana care sunt lucrate de catre acesta.
# Utilitatea
Utilitatea acestei baze de date este sa poata intregistra produsele achiztionate, cantitatea,pretul, data comenzii , metoda de plata. Aceste date sunt utile pentru analiza performantei magazinului.
Baza de date poate sa pastreze informatii despre clienti, cum ar  fi numele, adresa, istoricul cumparaturilor.Acest lucru faciliteaza gestionarea relatiilor cu clientii.
# Functionalitati
Aceasta baza de date stocheaza informatii despre produsele disponibile in magazin, inculsiv detalii despre tipul produsului, anul in care a aparut produsul, omul care l-a facut, genul de continut.Acest lucru permite monitorizarea si gestionarea eficienta a inventarului.
