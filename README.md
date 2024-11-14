# Telekonsultacje zdrowotne 
Telekonsultacje umożliwiają pacjentom uzyskanie porady medycznej bez konieczności fizycznej wizyty w gabinecie lekarskim. Pacjenci mogą kontaktować się z lekarzami za pośresdnictwem wideokonferencji, telefonu lub komunikatorów internetowych. 
Cele: Poprawa dostępności do usług zdrowotnych oraz obniżenie kosztów leczenia.

Korzyści dla pacjentów: 
- Oszczędność czasu dzięki braku konieczności dojazdu. 
- Szybszy dostęp do specjalistów. 
- Możliwość uzyskania porady z dowolnego miejsca.

Projekt zawiera następujące pliki:
- plik *opis_usługi.txt* zawierający opis usługi oraz korzyści dla pacjentów
- plik *plan_wdrożenia.txt* zawierający etapy wdrożenia
- plik *ryzyka.txt* zawierający potencjalne ryzyka związane z brakiem łączności, zabezpieczeniem danych pacjentów i wykonania badania in-vivo
- plik *ankieta_pacjentów.txt* zawierający pytania do ankiety
- plik *kampania_marketingowa.txt* zawierający metody reklamy usługi

## Aby sklonować to repozytorium użyj polecenia
```
git clone https://github.com/tkomo53/new_service_4776.git
```
lub
```
git clone git@github.com:tkomo53/new_service_4776.git
```

## Aby sprawdzić dostępne gałęzie i sprawdzić na jakiej aktualnie się znajdujesz, użyj polecenia
```
git branch
```

## Aby przełączyć się na inną gałąź użyj
```
git checkout <nazwa_gałęzi>
```


## Aby utworzyć nową gałąź użyj polecenia
```
git branch <nazwa_gałęzi>
```

Historię zmian w repozytorium zobaczysz używając polecenie `git log`

Jeśli chcesz przywrócić konkretny plik do wersji danej rewizji użyj polecenia
```
git checkout <hash_rewizji> -- <ścieżka/do/pliku>
```

Jeśli chcesz przywrócić cały projekt do stanu ze wskazanej rewizji użyj
```
git reset --hard <hash_rewizji>
```

## Informacja o wykorzystywanych poleceniach w projekcie
W projekcie używałem m.in.
`touch` - tworzenie nowego pliku
`mkdir` - tworzenie nowego folderu
`notepad <nazwa_pliku>` - edycja pliku w notatniku
`cat <nazwa_pliku>` - podejrzenie zawartości pliku
`git init` - inicjalizacja lokalnego repozytorium
`git add` - dodanie pliku/folderu do trybu staging
`git commit -m "tresc commita"` - dodanie rewizji z treścią
`git merge <nazwa_brancha>` - scalenie gałęzi na której się znajdujemy z gałęzią o podanej nazwie
`git merge --no-ff <nazwa_brancha>` - scalenie gałęzi na której się znajdujemy z gałęzią o podanej nazwie, z 
uwzględnieniem dodatkowego commita informującego o scaleniu
`git status`- sprawdzenie stanu niezacomittowanych plików w projekcie
`git remote add origin <adres_url>` - połączenie lokalnego repozytorium ze zdalnym
`git push` - wypchnięcie zmian z lokalnego repozytorium do repozytorium zdalnego
`git tag -a <wersja> -m <opis>` - dodanie tagu do repozytorium z opisem

## Opis problemów
- w niektórych miejscach nie było wskazane aby zatwierdzić zmiany, choć zatwierdzenie było wymagane aby kontynuować polecenia
- początkowo nie wiedział w jaki sposób zmergować gałęzie między którymi nie występuje konflikt tak,
  aby dodać commit z informacją o scaleniu. "Scalono gałąź marketing z główną gałęzią".
  W celu rozwiązania problemu zajrzałem do oficjalnej dokumentacji git (https://git-scm.com/doc)
- również w dokumentacji dowiedziałem się, w jaki sposób wypchnąc informację o dodanym tagu do repozytorium zdalnego 

