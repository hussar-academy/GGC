# Geek Girls Carrots

### Instalacja środowiska Node.JS oraz NPM dla systemu Windows:

* Pobierz ze strony https://nodejs.org/ plik instalacyjny Node.JS (stabilna wersja v4.4.3 LTS) dla odpowiedniej wersji Twojego systemu (32-bit lub 64-bit).
* Uruchom proces instalacyjny z pobranego pliku (plik z rozszerzeniem .msi lub .exe pobrany w punkcie pierwszym).
* Postępuj dalej z instalacją potwierdzając przyciskiem "Next" kolejne kroki instalacji.
* Po zakończonej instalacji w systemie windows dostępna będzie nowa linia poleceń o nazwie "Node.JS command prompt".
* Po uruchomieniu Node.JS command prompt wpisz ```node -v && npm -v``` w celu weryfikacji czy instalacja zakończyła się sukcesem. Konsola powinna zwrócić dwie wartości - pierwsza określa zainstalowaną wersję Node.JS, druga - wersję NPM.

### Instalacja środowiska Node.JS oraz NPM dla systemu Linux:

* Otwórz konsole poprzez nacisnięcie skrótu klawiszowego: Ctrl+Alt+T.
* W celu podlinkowania paczki należy wpisać w oknie konsoli:
```
curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
```
* Następnie należy pobrać Node.JS wpisując w konsoli:
```
sudo apt-get install -y nodejs
```
* Sprawdź poprawność zainstalowanej paczki wpisując:
```
node -v && npm -v
```
* Konsola powinna zwrócić dwie wartości - pierwsza określa zainstalowaną wersję Node.JS, druga - wersję NPM.

### Instalacja środowiska Node.JS oraz NPM dla systemu OSX:

#### 1. sposób:
* Istnieje możliwość pobrania pliku instalacyjnego z oficialnej strony (https://nodejs.org/). Kroki instalacyjne są bardzo podobne do tych które podejmowane były w trakcie instalacji pakietu w środowisku Winsows.

#### 2. sposób:
* Zainstaluj homebrew (http://brew.sh/), wpisując w konsoli:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
* Następnie:
```
brew install node
```
* Sprawdź czy NPM i Node.JS są poprawnie zainstalowane w systemie:
```
node -v && npm -v
```
* Konsola powinna zwrócić dwie wartości - pierwsza określa zainstalowaną wersję Node.JS, druga - wersję NPM.

### Instalacja GIT:
* Proces instalacyjny dostępny na oficjalnej stronie GIT (https://git-scm.com/book/pl/v1/Pierwsze-kroki-Instalacja-Git)

### Pobranie i uruchomienie aplikacji:
* Aby pobrać projekt na dysk twardy komputera, w oknie terminala wpisz:
```
git clone https://github.com/monterail/ggc
```
* Aby przejść do folderu z projektem:
```
cd ggc
```
* Pozostając jeszcze w oknie terminala, należy pobrać zależności z pliku ```package.json``` do katalogu ```node_modules```. Dokonujemy tego wpisując:
```
npm install
```
* Po krótkiej chwili oczekiwania, wszystkie zależności zostaną pobrane na lokalny dysk twardy. Następnie wpisz w oknie terminala:
```
npm run start
```
* Aby uruchomić aplikację w oknie przeglądarki, wejdź pod adres:
```
http://localhost:8080
```
