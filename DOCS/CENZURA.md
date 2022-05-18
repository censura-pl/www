
## Cenzura w sieci [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/CENZURA.md)

###  Zgłoszenia

## Zgłoszenia do CSIRT NASK

+ [Zgłoś incydent - CERT.PL>_](https://incydent.cert.pl/#!/lang=pl)
 
Od dnia 28 sierpnia 2018 r. zespołowi CERT Polska zostały powierzone obowiązki **CSIRT NASK** wynikające z ustawy z dnia 5 lipca 2018 r. o krajowym systemie cyberbezpieczeństwa (Dz. U. poz. 1560).

Zgłoszenia:

+ [Zgłaszanie osoby kontaktowej do CSIRT NASK](https://incydent.cert.pl/osoba-kontaktowa#!/lang=pl).
+ [Zgłaszanie domeny internetowej służącej do wyłudzeń danych i środków finansowych](https://incydent.cert.pl/domena#!/lang=pl).


### Blokada domeny

Na stronie NASK odnośnie statusów jest zawarta informacja, iż te statusy nie są dostępne publicznie:

"Dozwolone operacje Uwaga! Właściwości domen mogą zostać zmodyfikowane poprzez nałożenie na nie statusów. 
Statusy powiązane z domenami nie są widoczne w bazie WHOIS."

+ [DNS - Krajowy Rejestr Domen](https://www.dns.pl/cykl_zycia_domeny_pl)

#### Stan domeny widoczny przy sprawdzaniu przez WHOIS to **"stan domeny"**

Przykładowy **stan domeny** to:

**"Trwa postępowanie wyjaśniające [REGISTERED, ze statusem clientHold/serverHold]"**

#### wyjaśnienie NASK:

"Utrzymywanie domeny zostało wstrzymane do czasu wyjaśnienia wątpliwości dotyczących współpracy z jej abonentem, np. w przypadku zaległości płatniczych u rejestratora, braku aktualizacji danych abonenta (pomimo wezwania), wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci."


#### Rodzi się pytanie:

+ Jak można odróżnić powód blokady z powodu płatności od blokady np. z powodu wyroku sądu?

+ Jak można odróżnić poszczególne przypadki blokady?

+ Jak rozumieć stwierdzenie: "wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci." ?
 

NASK w ramach cenzury, czyli blokady bez wyroku sądu, nie tworzy nowego stanu/statusu dostępnego publicznie

#### Kto zna powód blokady domeny?

Skąd mógłbym otrzymać precyzyjniejszą informację zamiast "Trwa postępowanie wyjaśniające ..." ?

Ten ogólny stan opisu domeny może określać co najmniej te 5 poniższych możliwości: 

1. Utrzymywanie domeny zostało wstrzymane do czasu wyjaśnienia wątpliwości dotyczących współpracy z jej abonentem,

2. Zaległość płatnicza

3. Blokada z powodu braku aktualizacji danych abonenta (pomimo wezwania),

4. Wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci

5. Złamanie prawa i zablokowanie na skutek wyroku sądowego



Aktualnie to wszystko figuruje jako jeden status, dobrze by było znać kontekst blokady, dziś nie mamy pewności, kto złamał prawo, czy rejestrator, NASK, CERT, ABW, Exatel, itd...

Stan techniczny domeny można samemu sprawdzić, ale intencja blokady jest znana tylko organizacji NASK
