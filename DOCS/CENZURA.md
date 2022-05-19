
## Cenzura w sieci [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/CENZURA.md)


###  Zgłoszenia

## Zgłoszenia do CSIRT NASK

+ [Zgłoś incydent - CERT.PL>_](https://incydent.cert.pl/#!/lang=pl)
 
Od dnia 28 sierpnia 2018 r. zespołowi CERT Polska zostały powierzone obowiązki **CSIRT NASK** wynikające z ustawy z dnia 5 lipca 2018 r. o krajowym systemie cyberbezpieczeństwa (Dz. U. poz. 1560).

Zgłoszenia:

+ [Zgłaszanie osoby kontaktowej do CSIRT NASK](https://incydent.cert.pl/osoba-kontaktowa#!/lang=pl).
+ [Zgłaszanie domeny internetowej służącej do wyłudzeń danych i środków finansowych](https://incydent.cert.pl/domena#!/lang=pl).


### Blokada domeny

+ [Rejestr Domen Ocenzurowanych](https://hazard.mf.gov.pl/)
+ [Lista Domen ocenzurowanych](https://hole.cert.pl/domains/domains.txt)

### Informacje WHOIS

Na stronie NASK odnośnie statusów jest zawarta informacja, iż te statusy nie są dostępne publicznie:

"Dozwolone operacje Uwaga! Właściwości domen mogą zostać zmodyfikowane poprzez nałożenie na nie statusów. 
Statusy powiązane z domenami nie są widoczne w bazie WHOIS."

+ [DNS - Krajowy Rejestr Domen](https://www.dns.pl/cykl_zycia_domeny_pl)

#### Stan domeny widoczny przy sprawdzaniu przez WHOIS to **"stan domeny"**

Przykładowy **stan domeny** to:

**"Trwa postępowanie wyjaśniające [REGISTERED, ze statusem clientHold/serverHold]"**

#### wyjaśnienie NASK:

"Utrzymywanie domeny zostało wstrzymane do czasu wyjaśnienia wątpliwości dotyczących współpracy z jej abonentem, np. w przypadku zaległości płatniczych u rejestratora, braku aktualizacji danych abonenta (pomimo wezwania), wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci."


#### Rodzą się niejasności i pytania:

+ Jak można odróżnić powód blokady z powodu płatności od blokady np. z powodu wyroku sądu?

+ Jak można odróżnić poszczególne przypadki blokady?

+ Jak rozumieć stwierdzenie: "wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci." ?
 

NASK w ramach cenzury, czyli blokady bez wyroku sądu, nie tworzy nowego stanu/statusu dostępnego publicznie


#### Kto zna rzeczywisty powód blokady domeny?

Skąd mógłbym otrzymać precyzyjniejszą informację niż: "Trwa postępowanie wyjaśniające ..." ?

Trudno określić co konkretnie może być to za wątpliwość, dlatego dobrze by było znać co ma na myśli NASK.
Ten ogólny opis stanu domeny może określać co najmniej te kilka poniższych możliwości: 

1. Utrzymywanie domeny zostało wstrzymane do czasu wyjaśnienia wątpliwości dotyczących współpracy z jej abonentem,
   + Wszystkie przypadki spoza listy poniżej

2. Zaległość płatnicza wynikająca z umowy (domeny nie jest opłacona mimo zawarcia umowy),

3. Blokada z powodu braku aktualizacji danych abonenta (pomimo wezwania),

4. Wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci
   1. Sieci wewnętrznej konkretnej organizacji
   2. Wszystkim użytkownikom internetu
   3. Dystrybutorowi punktu dostępowego, zarządcy NASK

5. Złamanie prawa i zablokowanie na skutek wyroku sądowego
   + prawa autorskie, np. spór o nazwę domenę, wykorzystanie zarejestrowanej nazwy
   + patenty
   + działalność zabroniona w Polsce


Aktualnie to wszystko figuruje jako jeden status, dobrze by było znać kontekst blokady, dziś nie mamy pewności, kto złamał prawo, czy rejestrator, NASK, CERT, ABW, Exatel, itd...

Stan techniczny domeny można samemu sprawdzić, ale intencja blokady jest znana tylko organizacji NASK i organizacji zlecającej blokadę.

Druga istotna kwestia to data zdjęcia blokady o czym nie zawsze jesteśmy informowani, niektóre domeny mimo upłynięcia określonego czasu
nadal pozostają zablokowane do rejestracji.

Instytucja utrzymywana z pieniędzy podatników powinna co namniej być transparentna tak jak są podatnicy, którzy muszą się tłumaczyć każdemu urzędowi.