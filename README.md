# Last.fm-application

Zadatak je bio implementirati Android aplikaciju koja dohvaća određene podatke sa Last.fm API-ja i ispisuje ih u fragmentima koji sadrže liste kreirane pomoću RecyclerView-a. Podaci koji se dohvaćaju su liste popisi najboljih izvođača i pjesama, a postoji i mogućnost pretraživanja izvođača. U tom slučaju se dohvaća popis izvođača koji su pronađeni za upisanu frazu. Fotografije izvođača i pjesama se dohvaćaju koristeći Bing Search API. Dohvaćeni podaci se pohranjuju u Firebase bazu podataka kako bi se omogućile nove mogućnosti. Ova aplikacija je nadogradnja aplikacije sa stručne prakse sa novim mogućnostima, a to su:

- prikaz profila izvođača sa osnovnim informacijama o izvođaču i njegovim pjesmama
- prikaz informacija o pjesmi sa, za početak, poveznicom na npr. Youtube gdje bi se mogla preslušati pjesma
- društveno umrežavanje
    - praćenje korisnika
    - „lajkanje“, ocjenjivanje, dijeljenje i komentiranje pjesama i izvođača
    - „lajkanje“, ocjenjivanje i komentiranje pjesama i izvođača koje su drugi korisnici podijelili na svom profilu (korisničkih objava na profilu)
    - prikaz korisničkog profila sa podijeljenim pjesmama i izvođačima
    - prikaz najslušanijih izvođača korisnika u aplikaciji
    - prikaz najslušanijih pjesama korisnika u aplikaciji
    - prikaz najbolje ocijenjenih pjesama korisnika u aplikaciji

Aplikacija je pisana u Java programskom jeziku, a korišten je uzorak MVVM.
