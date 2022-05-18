

# [censura.pl](http://www.censura.pl/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/MENU.md)

Projekt badawczy mający na celu zrozumienie zasady działania cenzury w sieci:

+ [Documentation - docs.censura.pl](http://docs.censura.pl/)
+ [News - blog.censura.pl](http://blog.censura.pl/)
+ [Logo - logo.censura.pl](https://logo.censura.pl/)




## O Projekcie [censura.pl](http://www.censura.pl/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/ABOUT.md)

Projekt badawczy mający na celu zrozumienie zasady działania cenzury w sieci, stosowane przez takie instytucje i organizacje jak:
+ ABW
+ CERT
+ NASK
+ EXATEL

+ [Repozytorium plików git censura-pl/www: bash.censura.pl](https://github.com/censura-pl/www)
+ [Projekt grabWHOIS](https://github.com/grabWHOIS)




## Więcej informacji [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/DOCS.md)

Operator narodowy, 5G w Polsce:

+ [Exatel jest przygotowany do roli operatora strategicznego 5G - Polska Agencja Prasowa SA](https://www.pap.pl/aktualnosci/news%2C980390%2Cexatel-jest-przygotowany-do-roli-operatora-strategicznego-5g.html)
Założenia projektu #Polskie5G obejmuje budowę, operowanie oraz rozwój na terytorium Polski hurtowej infrastruktury technicznej dla sieci 5G zgodnie z trendem „network sharing” oraz przy założeniu:
+ stworzenia wspólnej sieci dostępowej dla wszystkich operatorów korzystających z infrastruktury,
+ zachowanie odrębności sieci rdzeniowej i warstwy usługowej,
+ synergii częstotliwości dla operatorów obecnie posiadający częstotliwości dla technologii 2G/3G/4G. Pozwoli to na łączenie częstotliwości tych operatorów z częstotliwością operatora hurtowego 5G co ma zwiększyć konkurencję na rynku.
+ [Exatel – narodowy operator 5G? | CyberDefence24](https://cyberdefence24.pl/polityka-i-prawo/exatelnarodowy-operator-5g)

Artykuły na temat bezpieczeństwa:

+ [Wiemy jak rząd ocenzuruje internet i wiemy jak się przed tym bronić - Zaufana Trzecia Strona](https://zaufanatrzeciastrona.pl/post/wiemy-jak-rzad-ocenzuruje-internet-i-wiemy-jak-sie-przed-tym-bronic/)

Rząd będzie zadowolony (przynajmniej początkowo), że zablokował, a internauci nie poczują w ogóle skutków blokady. A to dlatego, że aby ją ominąć, wystarczy:

+ zmienić adresy serwerów DNS w systemie operacyjnym lub na ruterze (np. na serwery Google lub OpenDNS),
+ skorzystać z dowolnego serwera proxy skonfigurowanego tak, by jego DNSy były poza Polską,
+ użyć VPNa,
+ użyć Tora,
+ użyć lokalnego pliku hosts, zawierającego adresy IP domen z czarnej listy,
+ użyć aplikacji innej niż przeglądarka, np. programu dostarczonego przez operatora serwisu hazardowego, który będzie miał zapisane na stałe adresy IP z którymi ma się łączyć.

### Oficjalna lista stron www / domen znajduje się tutaj:

+ [Rejestr Domen Ocenzurowanych](https://hazard.mf.gov.pl/)
+ [Lista Domen ocenzurowanych](https://hole.cert.pl/domains/domains.txt)


### Cykl życia nazwy zarejestrowanej w domenie .pl

+ [DNS - Krajowy Rejestr Domen](https://www.dns.pl/cykl_zycia_domeny_pl)


![Cykl życia nazwy domeny .pl](https://www.dns.pl/sites/default/files/images/Cykl_zycia_domeny1.png)

Pojęcia użyte w schemacie:

- **REGISTERED** - jedyny stan, w którym domena JEST eksportowana do DNS.

- **X dni** - okres, po którym domena zmienia stan, jeśli nie została wcześniej zarejestrowana lub odnowiona.

- **NASK** - NASK może występować jako Rejestr świadczący usługę, który w procesie zawierania umowy, tworzy domenę w stanie RESERVED (w następstwie realizacji opcji albo po prawomocnym orzeczeniu sądowym) lub przenosi domenę w stan DELETE\_BLOCKED (w procesie rozwiązywania umowy).

- **Uprawniony rejestrator** - rejestrator obsługujący nazwę domeny.

- **Odnowienie** - przedłużenie opłaconego okresu utrzymywania domeny za pośrednictwem uprawnionego rejestratora. Maksymalną wartość odnowienia na 11 lat można uzyskać odnawiając domenę na 10 lat, jednocześnie przesuwając okres rozliczeniowy o kolejnych 365 dni.

- **Brak odnowienia** - umowa po wypowiedzeniu (usługa nieaktywna). Możliwe odnowienie za pośrednictwem rejestratora.
 

### Statusy domen

+ [Statusy przy domenach - o czym mówią? co oznaczają? - Blog Domeny.tv](https://blog.domeny.tv/statusy-przy-domenach/)



## Cenzura w sieci [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/CENZURA.md)

Na stronie NASK odnośnie statusów jest zawarta informacja, iż te statusy nie są dostępne publicznie:

"Dozwolone operacje Uwaga! Właściwości domen mogą zostać zmodyfikowane poprzez nałożenie na nie statusów. 
Statusy powiązane z domenami nie są widoczne w bazie WHOIS."

+ [DNS - Krajowy Rejestr Domen](https://www.dns.pl/cykl_zycia_domeny_pl)

To co jest widoczne w przypadku domeny sprawdzanej narzędziem WHOIS to "stan domeny"

Przykładowy stan domeny to:

"Trwa postępowanie wyjaśniające [REGISTERED, ze statusem clientHold/serverHold]"

wyjaśnienie NASK to:

"Utrzymywanie domeny zostało wstrzymane do czasu wyjaśnienia wątpliwości dotyczących współpracy z jej abonentem, np. w przypadku zaległości płatniczych u rejestratora, braku aktualizacji danych abonenta (pomimo wezwania), wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci."


Rodzi się pytanie:
+ Jak można odróżnić Blokadę z powodu płatności od blokady z powodu cenzury?

Jak można odróżnić te wsyzstkie przypadki jakie zawiera tak ogólne "wyjaśnienie"?

 " wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci."
 
NASK w ramach cenzury, czyli blokady bez wyroku sądu, nie tworzy nowego stanu/statusu dostępnego publicznie

Co jeśli chciałbym znać powód blokady domeny?

Czy mógłbym otrzymać precyzyjniejsża informację zamiast "Trwa postępowanie wyjaśniające ..." ?
Ten ogólny stan opisu domeny może określać co najmniej te 5 poniższych możliwości: 

1. Utrzymywanie domeny zostało wstrzymane do czasu wyjaśnienia wątpliwości dotyczących współpracy z jej abonentem,

2. Zaległość płatnicza

3. Blokada z powodu braku aktualizacji danych abonenta (pomimo wezwania),

4. Wykorzystywania domeny do celów zagrażających bezpieczeństwu sieci

5. Złamanie prawa i zablokowanie na skutek wyroku sądowego



Aktualnie to wszystko figuruje jako jeden status, dobrze by było znać kontekst blokady, dziś nie mamy pewności, kto złamał prawo, czy rejestrator, NASK, CERT, ABW, Exatel, itd...

Stan technicznczny domeny można samemu sprawdzić, ale intencja blokady jest znana tylko organizacji NASK


## Przydatne Narzędzia [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/TOOLS.md)


### DNS 

Jak sprawdzić status domeny i dane abonenta?
+ [DNS - Krajowy Rejestr Domen](https://www.dns.pl/whois)

Globalna Lista usuniętych domen
+ [Deleted Domains (last 7 days) » ExpiredDomains.net](https://member.expireddomains.net/domains/combinedexpired/?o=statustld_registered&r=d&ftlds[]=196&flimit=200&fwordpl=1#listing)

+ [ WHOIS, DNS, & Domain Info - DomainTools](https://whois.domaintools.com/example.pl)

+ [ Reverse NS Lookup - DomainTools](https://reversens.domaintools.com/search/?q=)


### Check DNS, EN

There are two ways that a domain name =DNS server map can be constructed:

Zone file access: some registries grant access to their zone files to their registrars and other entities.
This makes it pretty easy to determine which domains in those zones are delegated to a given DNS server.
This is how DomainTools.com provides their Name Server Spy product.
This is the most reliable method, but is obviously limited to the zone files that they have access to.


Passive DNS. This involves examining traffic through recursive DNS servers at ISPs
and reconstructing zone data based on what's seen.
This method lets you discover information from the entire DNS space,
but is less reliable as changes take longer to appear in your database,
and won't recover information about domains that get little or no queries.



## Another Solutions

+ [Domain Whois Search - Whois lookup - GetWhois.com](http://getwhois.com/)
+ [getWHOIS](https://getwhois.io/softreck.com#)


## Planowane zmiany [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/TODO.md)

### Zawartość strony

+ Aktulane informacje o skali problemu
+ Wywiady z firmami rejestrującymi domeny na temat kontroli i problemów
+ Pytania do organizacji stosujących cenzurę 
+ Pytania do organizacji/osób, które są ofiarami tych działań 

### Narzędzia

W fazie testowania są dwa projekty:
+ grabWHOIS - bezpłatne narzedzie do pobierania danych WHOIS domeny
+ WHOISarch - odpłatne narzędzie z monitorowaniem i syngalizowaniem, pobierające WHOIS z wielu serwerów jednocześnie, kolejkowaniem list domen do sprawdze4nia
Powstają kolejne następne do monitorowania infrastruktury publicznej i prywatnej


# Statusy domen globalnych [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/STATUSY.md)

clientHold https://icann.org/epp#clientHold

clientTransferProhibited https://icann.org/epp#clientTransferProhibited

pendingDelete https://icann.org/epp#pendingDelete

serverHold https://icann.org/epp#serverHold

autoRenewPeriod https://icann.org/epp#autoRenewPeriod

redemptionPeriod https://icann.org/epp#redemptionPeriod


## [EPP Status Codes | What Do They Mean, and Why Should I Know? - ICANN](https://www.icann.org/resources/pages/epp-status-codes-2014-06-16-en#clientHold)

### Server Status Codes are Set by Your Domain's Registry

+ RDAP Status Mapping
+ EPP Status Code
+ What does it mean?
+ Should you do something?

### add period

    addPeriod

This grace period is provided after the initial registration of a domain name. If the registrar deletes the domain name during this period, the registry may provide credit to the registrar for the cost of the registration.

This is an informative status set for the first several days of your domain's registration. There is no issue with your domain name.

### auto renew period

    autoRenewPeriod

This grace period is provided after a domain name registration period expires and is extended (renewed) automatically by the registry. If the registrar deletes the domain name during this period, the registry provides a credit to the registrar for the cost of the renewal.

This is an informative status set for a limited time after your domain's auto- renewal by the registry. If you do not want to keep it (i.e., pay the renewal fee) anymore, you should contact your registrar immediately to discuss what options are available.

### inactive

    inactive

This status code indicates that delegation information (name servers) has not been associated with your domain. Your domain is not activated in the DNS and will not resolve.

If your domain has remained in this status for several days, you may want to contact your registrar to request information about the delay in processing.

If the TLD requires documentation to be provided for registration, you may need to provide the required documentation.

### active

    ok

This is the standard status for a domain, meaning it has no pending operations or prohibitions.

Asking your registrar to enact status restrictions, like clientTransferProhibited, clientDeleteProhibited, and clientUpdateProhibited, can help to prevent unauthorized transfers, deletions, or updates to your domain.

### pending create

    pendingCreate

This status code indicates that a request to create your domain has been received and is being processed.

If the TLD is on a special registration period (e.g. sunrise), this may indicate that the domain name will be allocated at the end of such period.

If the TLD is not on a special registration period and you are NOT the listed Registrant, you should contact your registrar immediately to resolve the issue.

### pending delete

    pendingDelete

This status code may be mixed with redemptionPeriod or pendingRestore. In such case, depending on the status (i.e. redemptionPeriod or pendingRestore) set in the domain name, the corresponding description presented above applies. If this status is not combined with the redemptionPeriod or pendingRestore status, the pendingDelete status code indicates that your domain has been in redemptionPeriod status for 30 days and you have not restored it within that 30-day period. Your domain will remain in this status for several days, after which time your domain will be purged and dropped from the registry database.

Once deletion occurs, the domain is available for re-registration in accordance with the registry's policies.

If you want to keep your domain name, you must immediately contact your registrar to discuss what options are available.

### pending renew

    pendingRenew

This status code indicates that a request to renew your domain has been received and is being processed.

If you did not request to renew your domain and do not want to keep it (i.e., pay the renewal fee) anymore, you should contact your registrar immediately to discuss what options are available.

### pending restore

    pendingRestore

This status code indicates that your registrar has asked the registry to restore your domain that was in redemptionPeriod status. Your registry will hold the domain in this status while waiting for your registrar to provide required restoration documentation. If your registrar fails to provide documentation to the registry operator within a set time period to confirm the restoration request, the domain will revert to redemptionPeriod status.

Watch your domain's status codes within this frequently defined seven day period to ensure that your registrar has submitted the correct restoration documentation within the time window. If this period ended and your domain has reverted back to a redemptionPeriod status, contact your registrar to resolve whatever issues that may have halted the delivery of your domain's required restoration documentation.

### pending transfer

    pendingTransfer

This status code indicates that a request to transfer your domain to a new registrar has been received and is being processed.

If you did not request to transfer your domain, you should contact your registrar immediately to request that they deny the transfer request on your behalf.

### pending update

    pendingUpdate

This status code indicates that a request to update your domain has been received and is being processed.

If you did not request to update your domain, you should contact your registrar immediately to resolve the issue.

### redemption period

    redemptionPeriod

This status code indicates that your registrar has asked the registry to delete your domain. Your domain will be held in this status for 30 days. After five calendar days following the end of the redemptionPeriod, your domain is purged from the registry database and becomes available for registration.

If you want to keep your domain, you must immediately contact your registrar to resolve whatever issues resulted in your registrar requesting that your domain be deleted, which resulted in the redemptionPeriod status for your domain. Once any outstanding issues are resolved and the appropriate fee has been paid, your registrar should restore the domain on your behalf.

### renew period
    
    renewPeriod

This grace period is provided after a domain name registration period is explicitly extended (renewed) by the registrar. If the registrar deletes the domain name during this period, the registry provides a credit to the registrar for the cost of the renewal.

This is an informative status set for a limited period or your domain's renewal by your registrar. If you did not request to renew your domain and do not want to keep it (i.e., pay the renewal fee) anymore, you should contact your registrar immediately to discuss what options are available.

### server delete prohibited

    serverDeleteProhibited

This status code prevents your domain from being deleted. It is an uncommon status that is usually enacted during legal disputes, at your request, or when a redemptionPeriod status is in place.

This status may indicate an issue with your domain that needs resolution. If so, you should contact your registrar to request more information and to resolve the issue. If your domain does not have any issues, and you simply want to delete it, you must first contact your registrar and request that they work with the Registry Operator to remove this status code.

Alternatively, some Registry Operators offer a Registry Lock Service that allows registrants, through their registrars to set this status as an extra protection against unauthorized deletions. Removing this status can take longer than it does for clientDeleteProhibited because your registrar has to forward your request to your domain's registry and wait for them to lift the restriction.

### server hold
    
    serverHold

This status code is set by your domain's Registry Operator. Your domain is not activated in the DNS.

If you provided delegation information (name servers), this status may indicate an issue with your domain that needs resolution. If so, you should contact your registrar to request more information. If your domain does not have any issues, but you need it to resolve in the DNS, you must first contact your registrar in order to provide the necessary delegation information.

### server renew prohibited

    serverRenewProhibited

This status code indicates your domain's Registry Operator will not allow your registrar to renew your domain. It is an uncommon status that is usually enacted during legal disputes or when your domain is subject to deletion.

Often, this status indicates an issue with your domain that needs to be addressed promptly. You should contact your registrar to request more information and resolve the issue. If your domain does not have any issues, and you simply want to renew it, you must first contact your registrar and request that they work with the Registry Operator to remove this status code. This process can take longer than it does for clientRenewProhibited because your registrar has to forward your request to your domain's registry and wait for them to lift the restriction.


### server transfer prohibited

    serverTransferProhibited

This status code prevents your domain from being transferred from your current registrar to another. It is an uncommon status that is usually enacted during legal or other disputes, at your request, or when a redemptionPeriod status is in place.

This status may indicate an issue with your domain that needs to be addressed promptly. You should contact your registrar to request more information and resolve the issue. If your domain does not have any issues, and you simply want to transfer it to another registrar, you must first contact your registrar and request that they work with the Registry Operator to remove this status code.

Alternatively, some Registry Operators offer a Registry Lock Service that allows registrants, through their registrars to set this status as an extra protection against unauthorized transfers. Removing this status can take longer than it does for clientTransferProhibited because your registrar has to forward your request to your domain's registry and wait for them to lift the restriction.


### server update prohibited

    serverUpdateProhibited

This status code locks your domain preventing it from being updated. It is an uncommon status that is usually enacted during legal disputes, at your request, or when a redemptionPeriod status is in place.

This status may indicate an issue with your domain that needs resolution. If so, you should contact your registrar for more information or to resolve the issue. If your domain does not have any issues, and you simply want to update it, you must first contact your registrar and request that they work with the Registry Operator to remove this status code.

Alternatively, some Registry Operators offer a Registry Lock Service that allows registrants, through their registrars to set this status as an extra protection against unauthorized updates. Removing this status can take longer than it does for clientUpdateProhibited because your registrar has to forward your request to your domain's registry and wait for them to lift the restriction.


### transfer period

    transferPeriod

This grace period is provided after the successful transfer of a domain name from one registrar to another. If the new registrar deletes the domain name during this period, the registry provides a credit to the registrar for the cost of the transfer.

This is an informative status set for a limited period or your domain's transfer to a new registrar. If you did not request to transfer your domain, you should contact your original registrar.

### Client Status Codes are Set by Your Domain's Registrar


### client delete prohibited

    clientDeleteProhibited

This status code tells your domain's registry to reject requests to delete the domain.

This status indicates that it is not possible to delete the domain name registration, which can prevent unauthorized deletions resulting from hijacking and/or fraud. If you do want to delete your domain, you must first contact your registrar and request that they remove this status code.


### client hold

    clientHold

This status code tells your domain's registry to not activate your domain in the DNS and as a consequence, it will not resolve. It is an uncommon status that is usually enacted during legal disputes, non-payment, or when your domain is subject to deletion.

Often, this status indicates an issue with your domain that needs resolution. If so, you should contact your registrar to resolve the issue. If your domain does not have any issues, but you need it to resolve, you must first contact your registrar and request that they remove this status code.


### client renew prohibited

    clientRenewProhibited

This status code tells your domain's registry to reject requests to renew your domain. It is an uncommon status that is usually enacted during legal disputes or when your domain is subject to deletion.

Often, this status indicates an issue with your domain that needs resolution. If so, you should contact your registrar to resolve the issue. If your domain does not have any issues, and you simply want to renew it, you must first contact your registrar and request that they remove this status code.


### client transfer prohibited

    clientTransferProhibited

This status code tells your domain's registry to reject requests to transfer the domain from your current registrar to another.

This status indicates that it is not possible to transfer the domain name registration, which will help prevent unauthorized transfers resulting from hijacking and/or fraud. If you do want to transfer your domain, you must first contact your registrar and request that they remove this status code.


### client update prohibited
 
    clientUpdateProhibited

This status code tells your domain's registry to reject requests to update the domain.

This domain name status indicates that it is not possible to update the domain, which can help prevent unauthorized updates resulting from fraud. If you do want to update your domain, you must first contact your registrar and request that they remove this status code.



---

+ [edit](https://github.com/censura-pl/www/edit/main/DOCS/ABOUT.md)
+ [censura-pl/www](https://github.com/censura-pl/www)
+ [LICENSE](LICENSE)

