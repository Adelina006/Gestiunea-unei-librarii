Proiectul consta in proiectarea si implementarea unei baze de date pentru gestiunea unei librarii. Tema aleasa are ca scop monitorizarea aprovizionarii si a relatiilor cu furnizorii(editurile), organizarea spatiului fizic si procesarea vanzarilor.
	Acest proiect a fost implementation SGDB Oracle, utilizand interfata sqldeveloper si contine notiuni fundamentale de baze de date, descrierea lucrarii, schema tabelelor si codul SQL.
Avem implementate in baza de date 8 tabele:

	tabela “Autori” care gestioneaza autorii cartilor din librarie, unde gasim date precum nume sau nationalitate

	tabela “Edituri” care gestioneaza editurile care furnizeaza stocurile de carti, unde gasim date precum nume sau data ultimei achizitii a librariei

	tabela ”Rafturi” care gestioneaza rafturile din librarie unde gasim capacitatea maxima, zona din librarie si de asemenea, un lucru care nu este comun in gestiunea unei librarii obisnuite, taxa per carte. Am adaugat acest element pentru a simula un model de gestiune financiara a spatiului. Aceasta taxa reprezinta plata pe care editura trebuie sa o achite pentru a-si putea expune cartile in anumite rafturi ( de ex rafturile din geam sau din intrarea librariei care ar putea atrage mai usor cumparatori).

	tabela “Zone” care gestioneaza zonele din librarie, unde gasim date precum numarul de angajati care lucreaza in acea zona sau suprafata

	tabela “Carti” care gestioneaza stocul de carti din librarie, unde gasim date precum autor, raft, pret de achizitie

	tabela “Clienti” care gestioneaza clientii librariei, unde gasim date precum nume sau numar de telefon

	tabela “Vanzari” care gestioneaza vanzarile librariei

	tabela “Rand_vanzare” care gestioneaza cartile din fiecare vanzare, unde gasim date precum numarul de carti vandute sau pretul de vanzare.

<img width="780" height="536" alt="image" src="https://github.com/user-attachments/assets/420537d6-35ad-4303-9bfd-158242c15c32" />
