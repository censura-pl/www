

## O Projekcie [censura.pl](http://www.censura.pl/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/ABOUT.md)
+ [Repozytorium plików git censura-pl/www: bash.censura.pl](https://github.com/censura-pl/www)

Projekt badawczy mający na celu zrozumienie zasady działania cenzury w sieci, stosowane przez takie instytucje i organizacje jak:

+ ABW, [Agencja Bezpieczeństwa Wewnętrznego](https://pl.wikipedia.org/wiki/Agencja_Bezpiecze%C5%84stwa_Wewn%C4%99trznego)
+ NASK, [Naukowa i Akademicka Sieć Komputerowa – Państwowy Instytut Badawczy](https://pl.wikipedia.org/wiki/Naukowa_i_Akademicka_Sie%C4%87_Komputerowa_%E2%80%93_Pa%C5%84stwowy_Instytut_Badawczy)
+ CERT, [CERT Polska – Wikipedia](https://pl.wikipedia.org/wiki/CERT_Polska)
+ EXATEL, [Exatel – Wikipedia](https://pl.wikipedia.org/wiki/Exatel)


## Więcej informacji [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/DOCS.md)

Operator narodowy, 5G w Polsce:

+ [Exatel jest przygotowany do roli operatora strategicznego 5G - Polska Agencja Prasowa SA](https://www.pap.pl/aktualnosci/news%2C980390%2Cexatel-jest-przygotowany-do-roli-operatora-strategicznego-5g.html)
Założenia projektu #Polskie5G obejmuje budowę, operowanie oraz rozwój na terytorium Polski hurtowej infrastruktury technicznej dla sieci 5G zgodnie z trendem „network sharing” oraz przy założeniu:
+ stworzenia wspólnej sieci dostępowej dla wszystkich operatorów korzystających z infrastruktury,
+ zachowanie odrębności sieci rdzeniowej i warstwy usługowej,
+ synergii częstotliwości dla operatorów obecnie posiadający częstotliwości dla technologii 2G/3G/4G. Pozwoli to na łączenie częstotliwości tych operatorów z częstotliwością operatora hurtowego 5G co ma zwiększyć konkurencję na rynku.
+ [Exatel – narodowy operator 5G? - CyberDefence24](https://cyberdefence24.pl/polityka-i-prawo/exatelnarodowy-operator-5g)

### Artykuły na temat bezpieczeństwa:

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

Stan techniczny domeny można samemu sprawdzić, ale intencja blokady jest znana tylko organizacji NASK i organizacji zlecającej blokadę.


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



## Bezpieczeństwo w sieci [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/SECURITY.md)

+ [Cyberwojna to fakt. Jak zabezpieczyć przed nią polską infrastrukturę krytyczną? - infoWire.pl](https://infowire.pl/generic/release/744042/cyberwojna-to-fakt-jak-zabezpieczyc-przed-nia-polska-infrastrukture-krytyczna#:~:text=Tylko%20w%202020,in%C5%BC.%20Andrzej%20Bartosiewicz)
## Statusy domen globalnych [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/STATUSY.md)

Jak sprawdzić?

+ [RFC 3912: WHOIS Protocol Specification](https://www.rfc-editor.org/rfc/rfc3912)

Lista Serwerów:

+ [nirsoft.net/whois-servers.txt](http://www.nirsoft.net/whois-servers.txt)

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



## Serwery WHOIS [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/censura-pl/www/edit/main/DOCS/SERWERY_WHOIS.md)

Lista Serwerów:

+ [nirsoft.net/whois-servers.txt](http://www.nirsoft.net/whois-servers.txt)
Maintained by Nir Sofer
This servers list if freely available for any use and without any restriction.
For more information: http://www.nirsoft.net/whois_servers_list.html
Last updated on 16/02/2016

    
        ac whois.nic.ac
        ad whois.ripe.net
        ae whois.aeda.net.ae
        aero whois.aero
        af whois.nic.af
        ag whois.nic.ag
        ai whois.ai
        al whois.ripe.net
        am whois.amnic.net
        as whois.nic.as
        asia whois.nic.asia
        at whois.nic.at
        au whois.aunic.net
        aw whois.nic.aw
        ax whois.ax
        az whois.ripe.net
        ba whois.ripe.net
        bar whois.nic.bar
        be whois.dns.be
        berlin whois.nic.berlin
        best whois.nic.best
        bg whois.register.bg
        bi whois.nic.bi
        biz whois.neulevel.biz
        bj www.nic.bj
        bo whois.nic.bo
        br whois.nic.br
        br.com whois.centralnic.com
        bt whois.netnames.net
        bw whois.nic.net.bw
        by whois.cctld.by
        bz whois.belizenic.bz
        bzh whois-bzh.nic.fr
        ca whois.cira.ca
        cat whois.cat
        cc whois.nic.cc
        cd whois.nic.cd
        ceo whois.nic.ceo
        cf whois.dot.cf
        ch whois.nic.ch
        ci whois.nic.ci
        ck whois.nic.ck
        cl whois.nic.cl
        cloud whois.nic.cloud
        club whois.nic.club
        cn whois.cnnic.net.cn
        cn.com whois.centralnic.com
        co whois.nic.co
        co.nl whois.co.nl
        com whois.verisign-grs.com
        coop whois.nic.coop
        cx whois.nic.cx
        cy whois.ripe.net
        cz whois.nic.cz
        de whois.denic.de
        dk whois.dk-hostmaster.dk
        dm whois.nic.cx
        dz whois.nic.dz
        ec whois.nic.ec
        edu whois.educause.net
        ee whois.tld.ee
        eg whois.ripe.net
        es whois.nic.es
        eu whois.eu
        eu.com whois.centralnic.com
        eus whois.nic.eus
        fi whois.fi
        fo whois.nic.fo
        fr whois.nic.fr
        gb whois.ripe.net
        gb.com whois.centralnic.com
        gb.net whois.centralnic.com
        qc.com whois.centralnic.com
        ge whois.ripe.net
        gg whois.gg
        gi whois2.afilias-grs.net
        gl whois.nic.gl
        gm whois.ripe.net
        gov whois.nic.gov
        gr whois.ripe.net
        gs whois.nic.gs
        gy whois.registry.gy
        hamburg whois.nic.hamburg
        hiphop whois.uniregistry.net
        hk whois.hknic.net.hk
        hm whois.registry.hm
        hn whois2.afilias-grs.net
        host whois.nic.host
        hr whois.dns.hr
        ht whois.nic.ht
        hu whois.nic.hu
        hu.com whois.centralnic.com
        id whois.pandi.or.id
        ie whois.domainregistry.ie
        il whois.isoc.org.il
        im whois.nic.im
        in whois.inregistry.net
        info whois.afilias.info
        ing domain-registry-whois.l.google.com
        ink whois.centralnic.com
        int whois.isi.edu
        io whois.nic.io
        iq whois.cmc.iq
        ir whois.nic.ir
        is whois.isnic.is
        it whois.nic.it
        je whois.je
        jobs jobswhois.verisign-grs.com
        jp whois.jprs.jp
        ke whois.kenic.or.ke
        kg whois.domain.kg
        ki whois.nic.ki
        kr whois.kr
        kz whois.nic.kz
        la whois2.afilias-grs.net
        li whois.nic.li
        london whois.nic.london
        lt whois.domreg.lt
        lu whois.restena.lu
        lv whois.nic.lv
        ly whois.lydomains.com
        ma whois.iam.net.ma
        mc whois.ripe.net
        md whois.nic.md
        me whois.nic.me
        mg whois.nic.mg
        mil whois.nic.mil
        mk whois.ripe.net
        ml whois.dot.ml
        mo whois.monic.mo
        mobi whois.dotmobiregistry.net
        ms whois.nic.ms
        mt whois.ripe.net
        mu whois.nic.mu
        museum whois.museum
        mx whois.nic.mx
        my whois.mynic.net.my
        mz whois.nic.mz
        na whois.na-nic.com.na
        name whois.nic.name
        nc whois.nc
        net whois.verisign-grs.com
        nf whois.nic.cx
        ng whois.nic.net.ng
        nl whois.domain-registry.nl
        no whois.norid.no
        no.com whois.centralnic.com
        nu whois.nic.nu
        nz whois.srs.net.nz
        om whois.registry.om
        ong whois.publicinterestregistry.net
        ooo whois.nic.ooo
        org whois.pir.org
        paris whois-paris.nic.fr
        pe kero.yachay.pe
        pf whois.registry.pf
        pics whois.uniregistry.net
        pl whois.dns.pl
        pm whois.nic.pm
        pr whois.nic.pr
        press whois.nic.press
        pro whois.registrypro.pro
        pt whois.dns.pt
        pub whois.unitedtld.com
        pw whois.nic.pw
        qa whois.registry.qa
        re whois.nic.re
        ro whois.rotld.ro
        rs whois.rnids.rs
        ru whois.tcinet.ru
        sa saudinic.net.sa
        sa.com whois.centralnic.com
        sb whois.nic.net.sb
        sc whois2.afilias-grs.net
        se whois.nic-se.se
        se.com whois.centralnic.com
        se.net whois.centralnic.com
        sg whois.nic.net.sg
        sh whois.nic.sh
        si whois.arnes.si
        sk whois.sk-nic.sk
        sm whois.nic.sm
        st whois.nic.st
        so whois.nic.so
        su whois.tcinet.ru
        sx whois.sx
        sy whois.tld.sy
        tc whois.adamsnames.tc
        tel whois.nic.tel
        tf whois.nic.tf
        th whois.thnic.net
        tj whois.nic.tj
        tk whois.nic.tk
        tl whois.domains.tl
        tm whois.nic.tm
        tn whois.ati.tn
        to whois.tonic.to
        top whois.nic.top
        tp whois.domains.tl
        tr whois.nic.tr
        travel whois.nic.travel
        tw whois.twnic.net.tw
        tv whois.nic.tv
        tz whois.tznic.or.tz
        ua whois.ua
        ug whois.co.ug
        uk whois.nic.uk
        uk.com whois.centralnic.com
        uk.net whois.centralnic.com
        ac.uk whois.ja.net
        gov.uk whois.ja.net
        us whois.nic.us
        us.com whois.centralnic.com
        uy nic.uy
        uy.com whois.centralnic.com
        uz whois.cctld.uz
        va whois.ripe.net
        vc whois2.afilias-grs.net
        ve whois.nic.ve
        vg ccwhois.ksregistry.net
        vu vunic.vu
        wang whois.nic.wang
        wf whois.nic.wf
        wiki whois.nic.wiki
        ws whois.website.ws
        xxx whois.nic.xxx
        xyz whois.nic.xyz
        yu whois.ripe.net
        za.com whois.centralnic.com
        
        


---

+ [edit](https://github.com/censura-pl/www/edit/main/DOCS/ABOUT.md)
+ [censura-pl/www](https://github.com/censura-pl/www)
+ [LICENSE](LICENSE)

