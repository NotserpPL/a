# 📖 Poradnik ttProxy

👋 **Witaj w przewodniku po ttProxy!** 🎮


#1 🚪 **Wejście na ttProxy**
Aby wejść na ttProxy, postępuj zgodnie z poniższymi krokami:

1. **Włącz Minecraft** 🟢
2. Wejdź w zakładkę **Multiplayer** 🖥️
3. Kliknij **"Dodaj serwer"** ➕
4. Wpisz adres IP **ttproxy.club** 🌐
5. Po wejściu na serwer, zarejestruj się komendą:  
   `,register <hasło> <hasło>` 🔑

Następnie w wyświetlonym GUI wybierz kanał chatu 💬, z którego chcesz korzystać.

> **Uwaga:** Prefix komend na ttProxy to przecinek **","**  
> 👉 Oznacza to, że komendy wpisujemy z przecinkiem, a nie "/", jak na innych serwerach!

---

## 🌍 **Dostępne wersje klienta**

Możesz wejść na ttProxy z dowolnej wersji Minecrafta, od **1.8** do **1.20.1**! 🕹️  
**Premium** oraz **Elite** mogą korzystać z wersji do **1.20.6** ⭐.

---

### ⚠️ **Zalecenia dotyczące wersji:**

- **Zalecana wersja**: 1.17.1 ✅
- **Niezalecane wersje**: 1.8x oraz 1.16x ⚠️ (mogą występować błędy 😵‍💫)

---

### 🎉 **Miłej zabawy na ttProxy!** 🎉


# 📜 Spis Komend

Wpis wszystkich komend znajduje się pod komendą:  
``,help`` 🆘

## 🗂️ **Porządek Komend**
Komendy w spisie są ułożone **alfabetycznie** od **A** do **Z** 🔤.  

## 📲 **Nawigacja po Spisie Komend**
Po wywołaniu komendy ``,help`` masz dwie możliwości, aby przemieszczać się po spisie:

1. **Użyj strzałek** na chacie ⬅️➡️.
2. **Wpisz ręcznie**: 
   - ``,help 1``
   - ``,help 2``
   - ``,help 3`` 
   - i tak dalej! 🔢

## 🖱️ **Pełny Wzór Komendy**
Gdy najedziesz kursorem na jedną z komend w ``,help``, wyświetli się pełny wzór tej komendy. 👀✨

Możesz również uzyskać ten sam wzór, wpisując początek komendy, a następnie klikając **Enter**. 🔄

### 📝 **Przykład**
Jeżeli wpiszesz komendę:  
``,connect`` 🔗  
Na chacie pojawi się pełny wzór komendy, co ułatwi jej użycie! 💡

---

### 🎉 **Miłej zabawy z komendami!** 🎉


# 🔗 Łączenie się na Serwer

Aby połączyć się z innymi serwerami, użyj komendy:  
``,connect`` 🌐

## 💡 **Czym jest komenda ,connect?**
Komenda ta przenosi Cię z lobby ttProxy na inny serwer Minecraft! 🎮  
Dzięki ttProxy możesz wejść na dowolny serwer Minecraft w **100% bezpiecznie** 🔒.  
Oferuje ona **zmianę nicku** oraz **zmianę IP** przy użyciu proxy.

---

## 📝 **Wzór Komendy**
Poniżej przedstawiam wzór komendy oraz opisy do każdego argumentu:
,connect <IP> <PORT> <PROXY> <NICK> <CHECKER[true/false]>

### 🔍 **Szczegóły Argumentów:**

1. **`<IP>`**:  
   Tutaj wpisz domenę serwera lub jego numer IP. 🌍

2. **`<PORT>`**:  
   Jeśli używasz domeny, wpisz **0** (zero) lub poprawny port, jeśli go znasz. 🔢

3. **`<PROXY>`**:  
   W tym argumencie wpisz nazwę listy proxy.  
   - Rangi BASIC oraz PREMIUM mają dostęp do:
     - **public:<kraj/all>**
     - **private:<kraj/all>** 
   - Ranga ELITE ma dostęp do tych samych list, ale z drobną różnicą:  
     Ranga ELITE domyślnie używa osobnych proxy do łączenia.  
     Może zmienić to pod komendą ``,proxytype`` ⚙️.

   **Lista dostępnych krajów** dla public znajduje się pod komendą: ``,proxylist``.  
   Dla private również znajdziesz ją pod komendą ``,proxylist`` oraz ``,proxytype``. 📋

   **Przykłady list proxy**: 
   - `public:all` 
   - `public:us` 
   - `private:all` 
   - `private:pl` 

4. **`<NICK>`**:  
   Tutaj wpisz dowolny nick, np. **BOB123**, lub skorzystaj z generatorów, takich jak:  
   - `[r]` – losowe litery i cyfry 🔤  
   - `[real]` – realistyczne nicki 👤  
   - `[n]` – same cyfry 🔢  

   Możesz również ustawić ilość znaków dla generatora, wpisując: 
   - `[r:7]` (7 losowych znaków) 
   - `[n:4]` (4 cyfry)  

   Możesz także łączyć generatory, np.:  
   - `Bob123[r:3]` 
   - `[real][n:2]` 

5. **`<CHECKER>`**:  
   To opcjonalna funkcja dla komendy ``,connect``.  
   Możesz wpisać tylko **true** lub **false**:  
   - **true**: podczas łączenia z public proxy, lista proxy będzie skanowana maksymalnie 20 proxy do przodu w poszukiwaniu działającego IP. 🔍  
   - **false**: przy użyciu private proxy nie musisz tego włączać.

---

## 🎉 **Przykłady użycia komendy ,connect**
Oto kilka przykładów:

- `,connect serwer.pl 0 private:pl [real] false`
- `,connect server.pl 0 public:us Maciek555 true`
- `,connect server.pl 0 public:all [r] true`
- `,connect server.pl 0 private:de John123_ false`

---

### 🎊 **Miłej zabawy w łączeniu się z serwerami!** 🎊


# 🤖 Łączenie Botów na Serwer

Aby połączyć boty, użyj komendy:  
``,connectbot`` 🌐

## 📜 **Wzór Komendy**
Po wpisaniu tej komendy wyświetli się pełny wzór komendy:
,connectbot <COUNT> <DELAY> <PROXY> <NICKNAME> <MACRO>


### 📝 **Szczegóły Argumentów:**

1. **`<COUNT>`**:  
   Tutaj wpisz **ilość botów**, które chcesz połączyć. 🔢

2. **`<DELAY>`**:  
   Określ odstęp w **milisekundach** między dołączaniem botów, np. **200**. ⏳

3. **`<PROXY>`**:  
   Wpisz nazwę listy proxy, której boty mają użyć.  
   - Ranga **BASIC** oraz **PREMIUM** ma dostęp tylko do:  
     **public:<kraj/all>** 🌍
   - Ranga **ELITE** ma dostęp do:  
     **public:<kraj/all>** oraz **private:<kraj/all>** 🔐

4. **`<NICKNAME>`**:  
   Tutaj wpisz nick, jaki mają mieć boty.  
   Opcje są takie same jak w komendzie ``,connect``. 👤

5. **`<MACRO>`**:  
   Możesz wpisać **ID** nagranego wcześniej makra lub wpisać **false**. 🎥

---

## ⚙️ **Działanie Komendy**
Po użyciu tej komendy boty zaczną łączyć się z serwerem, na którym jesteś aktualnie połączony. 🌐

**Uwaga:**  
Komendę ``,connectbot`` można używać wielokrotnie, ale **nie zaleca się spamowania**, ponieważ przerywa to poprzednie połączenia botów i rozpoczyna je od nowa. ❌

Jeśli chcesz użyć komendy kilka razy dla lepszego efektu, odczekaj, aż większość botów się połączy lub podejmie próbę połączenia. ⏳

---

## 🤖 **Rodzaje Botów na ttProxy**

Na ttProxy dostępne są **2 rodzaje botów**:

1. **Boty standardowe**:  
   - Dostępne dla rangi **BASIC** oraz **PREMIUM**. 🆕

2. **Boty z fizyką**:  
   - Dostępne tylko dla rangi **ELITE**. 🌟  
   - **Różnice**: Boty z fizyką są bardziej realistyczne. Grawitacja, kolizja, knock z uderzenia itp. sprawiają, że zachowują się jak prawdziwi gracze! ⚖️

Funkcja fizyki botów pozwala na obejście wielu antybotów, które sprawdzają, czy gracz posiada taką fizykę. 🚫🤖

---

### 🎉 **Miłej zabawy z botami na serwerze!** 🎉


# 📝 Rejestracja Botów / Autorejestracja

Istnieją **2 sposoby rejestracji botów**: 

## 1️⃣ **Rejestracja za pomocą komendy**
Użyj komendy:  
,register

Opcjonalnie, możesz wpisać hasło:  
,register <haslo>

Wtedy wszystkie połączone boty w jednym momencie wyślą komendy:  
/register <haslo> <haslo> oraz /login <haslo>

Możesz użyć tej komendy w **dowolnym momencie**! ⏰

---

## 2️⃣ **Rejestracja za pomocą autorejestracji**
Drugą opcją rejestracji botów jest komenda:  
,autoregister

Po wpisaniu tej komendy wyświetli się **GUI**, w którym masz cały panel konfiguracyjny. 🖥️

### 🛠️ **Konfiguracja w GUI**
- Możesz ustawić dla kogo ma być rejestracja:  
  - **Dla nas**  
  - **Dla botów**  
  - **Dla obydwu**  

Domyślnie wszystkie wartości w GUI wystarczają dla większości serwerów, ale jeśli potrzebujesz, możesz **dostosować konfigurator** autorejestracji, aby lepiej wykrywał, kiedy zachodzi rejestracja lub logowanie. ⚙️

### ⚡ **Dostosowanie Komend**
Możesz również ustawić **customowe komendy**, których boty mają użyć do rejestracji, jeśli zajdzie taka potrzeba. 📝

---

### 🎉 **Miłej zabawy z rejestracją botów!** 🎉


# 🎮 Sterowanie Botami / Pisanie Nimi

Botami można sterować na **2 sposoby**:  
Służą do tego **2 funkcje**:

1. **`,mother`** - Boty naśladują Twoje pakiety w czasie rzeczywistym. 🔄  
2. **`,macro`** - Możliwość nagrania i odtworzenia pakietów dla botów w dowolnym momencie. 🎥

---

## 1️⃣ **Funkcja MOTHER**

W obu przypadkach boty wykonują to, co my, ale różnica jest taka, że boty na ``,mother`` naśladują nas w czasie rzeczywistym. ⏱️

### 📍 **Zastosowanie:**
Jest to przydatne, gdy chcemy szybko przemieścić boty z punktu A do punktu B. 🛤️

### 🛠️ **Jak Używać:**
1. **Połącz boty**. 
2. Wpisz komendę:  
,mother


#### **Opcje Konfiguracyjne:**

- Aby ustawić opóźnienie między botami, użyj:  
,mother <delay>

Przykład:  
,mother 200

- Domyślnie ustawienie to **0**.  
- Maksymalne opóźnienie to **5000 ms** (czyli 5 sekund). ⏳

- **``,motherdistance <odległość>``**:  
Umożliwia ustawienie, w jakiej odległości od Ciebie boty mają kopiować Twoje pakiety ruchu (chodzenia).  
- Domyślnie boty kopiują pakiety, gdy jesteś w pobliżu jednego bloku.  
- Jeżeli chcesz, aby boty teleportowały się z większego dystansu, ustaw większą wartość, np. **10** lub **0** (gdzie 0 oznacza, że boty będą kopiować pakiety z każdej odległości). 📏

- **``,mothersettings``**:  
Dzięki tej funkcji możesz wybrać, które konkretne boty mają kopiować Twoje pakiety i podążać za Tobą.  
- Domyślnie wszystkie boty kopiują Twoje ruchy, ale możesz to zmienić, jeśli chcesz sterować np. tylko jednym botem. 🎮

### ⚠️ **Dodatkowe Uwagi dla Używania MOTHER:**
- Boty muszą być **zarejestrowane / zalogowane**. 🔑
- Aby boty zaczęły za Tobą chodzić, musisz wejść na ten sam blok, na którym stoją boty. 🧍‍♂️
- Zaleca się najpierw stanąć tam, gdzie są boty, a potem włączyć ``,mother``. ✔️

---

### 🎉 **Miłej zabawy z kontrolowaniem botów!** 🎉


# 🎥 MACRO

**Drugą funkcją** jest funkcja **`,macro`**.  
Jest ona nieco bardziej skomplikowana i wymagająca, dlatego zazwyczaj korzystają z niej osoby z większym doświadczeniem w obsłudze ttProxy. 🌟

## 🛠️ **Dwa Sposoby Korzystania z Macra**

### 1️⃣ **GUI (Interfejs Graficzny)**

Najprostszy sposób korzystania z macra to GUI, które znajduje się pod komendą:  
,macro

W tym GUI znajdziesz większość rzeczy, które pozwolą łatwo korzystać z tej funkcji. 💻

### 📋 **Elementy GUI:**

- 🟢 **Przycisk rozpoczęcia/zakończenia nagrywania macra**
- ▶️ **Przycisk uruchomienia wybranego macra**
- 🕳️ **Puste sloty na nagrane macra lub nagrane macra, jeśli są**
- ⏹️ **Przycisk zatrzymania odtwarzanego macra**
- 🔁 **Przycisk do zmiany trybu odtwarzania (pojedyncze odtworzenie lub w nieskończoność)**
- 🎮 **Przycisk do zmiany trybu macra (BOTS lub Player — dla siebie samego)**

### 🚀 **Przykład Nagrania i Uruchomienia Macra:**

1. Wchodzimy na serwer i wpisujemy:
,macro

2. Następnie klikamy przycisk **macro rec**.  
Okno się zamknie i możemy nagrywać to, co robimy (np. biegać po spawnie serwera). 🏃‍♂️

3. Gdy chcemy zakończyć nagrywanie, ponownie wpisujemy:
,macro

i klikamy przycisk **macro rec**.

4. Na środku GUI zobaczymy nasze nagranie w **slocie nr 1**.  
Możemy kliknąć na nie lewym przyciskiem myszy, aby je zaznaczyć. ✔️

5. Po zaznaczeniu nagranego macra, klikamy przycisk **macro load**, a połączone boty zaczną odtwarzać to, co nagraliśmy. 🎉

Oczywiście, istnieje wiele możliwości konfiguracji. Możesz nauczyć się, jak uruchamiać macra dla pojedynczych botów, jak zapętlać je w nieskończoność itp. 🔄

---

### 2️⃣ **Korzystanie z Komend**

Spis komend dla macra można znaleźć pod komendą:  
,macro help

Znajdziesz tam takie komendy jak: 

- 🎤 **`,macro rec`** - nagrywanie macra
- ▶️ **`,macro load`** - odtwarzanie macra przez boty
- 🎮 **`,macro player`** - odtwarzanie macra przez siebie
- ⏱️ **`,macro delay`** - możliwość zmiany odstępu dla botów podczas uruchamiania macra
- 📏 **`,macro distance`** - ustawienie odległości, z której boty mają wykonywać macro
- 📜 **`,macro list`** - wyświetla listę nagranych macr
- ❌ **`,macro clear`** - usuwa nagrane macro
- ⏹️ **`,macro stop`** - zatrzymuje macro/macra
- 🗺️ **`,macro tracer`** - pokazuje trasę macra
- 📝 **`,macro name`** - pozwala dodać opis do macra

Znajdziesz tam również opisy oraz przykłady użycia. 📚

---

### 💡 **Ciekawostki i Przydatne Informacje:**

- Nagrywanie macra można rozpocząć jeszcze przed użyciem komendy **`,connect`**.  
  (Przydatne, gdy chcemy użyć macra w connectbot, aby bot uruchamiał macro od razu po wejściu.) 🚀

- Można odtwarzać kilka macr w tym samym czasie!  
  (W GUI wystarczy zaznaczyć więcej niż jedno macro, a w **`,macro load`** wystarczy wpisać ID macr po przecinku, np. **1,2,3**. To samo w `<macro>` w komendzie **`,connectbot`**.)

- W **`,macro`** po kliknięciu prawym przyciskiem myszy na nagrane ID macra, możesz wybrać, które konkretne boty mają odtwarzać dane macro. 🎯

- W **`,macro list`** można kliknąć "save", co spowoduje, że macro zostanie zapisane na stałe, i będzie można je odtwarzać, aż do momentu, gdy zostanie przez nas usunięte ręcznie. 💾

- Nagrane macro można nazwać w dowolny sposób, aby opisać do czego służy lub zapisać jego koordynaty. 🗺️

- Możliwość odpalenia macra po ponownym połączeniu bota poprzez włączenie tej opcji w **`,autoreconnect`**. 🔄

- **`,macro distance`** działa na identycznej zasadzie jak **`,motherdistance`**.  
  Jeżeli boty będą w innym miejscu niż odbywa się macro, to nie będą wysyłać pakietów od pozycji. ❗

---

### 🎉 **Miłej zabawy z korzystaniem z macra!** 🎉


# 📢 Broadcasting with Bots

Aby pisać samymi botami na chacie, mamy do dyspozycji takie funkcje jak:

- **`,bc`** - Pojedyncze wysyłanie wiadomości botami. ✉️
- **`,bcinfinity`** - Wysłanie wiadomości, która automatycznie się zapętla i wysyła w nieskończoność. 🔄

## 📜 **Wzór Komendy dla `,bc`**
,bc <smooth/add/list> <text>


### 🛠️ **Parametry Komendy:**

- **`smooth`**: Wpisz wartość od **0 do 500** (ms). Oznacza to, co ile milisekund każdy bot ma wysyłać po sobie wiadomość/komendę. ⏱️
- **`add`**: Funkcja, która pozwala dodać "słowo" do listy, a następnie słowa z listy zostaną użyte do **`,bcinfinity`**. 📚
- **`list`**: Wyświetla listę dodanych słów za pomocą funkcji **add**. 📋
- **`text`**: Tutaj wpisujemy wiadomość. 💬

### 📝 **Przykłady Użycia `,bc`:**
,bc 30 ttProxy jest najlepsze <3 ,bc add Hejka ,bc list

---

## 📜 **Wzór Komendy dla `,bcinfinity`**
,bcinfinity <smooth/stop> <delay> <player/bots> <text/multi[true]>


### 🛠️ **Parametry Komendy:**

- **`smooth`**: To samo co przy komendzie **`,bc`**. ⏱️
- **`stop`**: Zatrzymuje pisanie wiadomości. 🛑
- **`delay`**: Odstęp między zapętlaniem się wiadomości. ⏳
- **`player/bots`**: Wybór, czy wiadomości mają być wysyłane przez nas, czy przez boty. 🤖👤
- **`text`**: Tutaj wpisujemy wiadomość. 💬
- **`multi`**: Ten sam argument co **`<text>`**, ale jeżeli mamy dodane słowa za pomocą komendy **`,bc add <text>`**, to zamiast pisać wiadomość w **`,bcinfinity`**, wpisujemy tam samo **"true"**. ✅  
  Wtedy boty zaczną spamić wiadomościami po kolei dodanych słów/zdań, np. w takiej kolejności:
  1. Witajcie 👋
  2. Co 🤔
  3. Tam 🌍
  4. U 🏠
  5. Was? ❓

### 📝 **Przykłady Użycia `,bcinfinity`:**
,bcinfinity 20 3500 bots ttProxy jest najlepsze <3 ,bcinfinity 50 3500 bots true ,bcinfinity 0 3000 player Hejka ttProxy jest the best. ,bcinfinity stop


---

## 💡 **Dodatkowe Informacje:**

Jeżeli chcesz, aby każda wiadomość różniła się od siebie, możesz w dowolnym miejscu w **`<text>`** wstawić **`[r:ilość]`**, np. **`[r:3]`**.  
Dzięki temu w tym miejscu zostaną wygenerowane 3 losowe litery. 🔤  
Można w ten sposób bypassować zabezpieczenia antyspam. 🚫

---

### 🎉 **Miłego korzystania z funkcji Broadcasting!** 🎉


# 🌍 Zmiana Wersji Bez Zmiany Clienta

Komenda **`,multiversion`** lub **`,mv`** pozwala ustawić dowolną wspieraną wersję Minecraft dla Ciebie oraz dla botów. Dzięki temu masz możliwość wejścia na serwer niezależnie od tego, na jakiej wersji znajduje się serwer, oraz na jakiej wersji klienta się znajdujesz. 🚀

## 📌 **Przykład Użycia:**

Jeżeli serwer jest np. na wersji **1.19.4**, a Ty jesteś na kliencie **1.17.1**, który domyślnie nie wspiera wersji **1.17.1**, możesz wpisać komendę:
,mv 1.19.4

To pozwoli Ci połączyć się na serwerze! 🎉

---

## ⚠️ **Uwaga:**

Zmiany wersji mogą wpływać na działanie klienta/botów. 🛠️

- Niektóre wersje mogą negatywnie oddziaływać na działanie **ttProxy** lub niektórych funkcji.
- W związku z tym, niektóre funkcje lub bypassy mogą działać lepiej lub gorzej na niektórych wersjach.

### 📊 **Zalecana Wersja:**

Wersja, która jest uważana za najbardziej stabilną i pozbawioną bugów to **1.17.1**. ✅

### 🔍 **Problemy z Wersjami:**

- Na wersjach niższych oraz wyższych mogą (ale nie muszą) występować błędy związane z fizyką botów, flagowaniem przez antycheaty itp.
- **Niezalecane wersje**: **1.8x** oraz **1.16x**. Te wersje mogą mieć problemy z tak zwanym **limbo**, a boty na tych wersjach są bardziej podatne na blokowanie przez antycheaty. 🚫

---

### 🎉 **Miłego korzystania z funkcji zmiany wersji!** 🎉


# 💥 Crashowanie

Do wysyłania pakietów obciążających serwer, służy komenda **`,crash`**. 💣

## 📜 **Pełny Wzór Komendy:**
,crash <metoda> <ilość pakietów> <window/slot/place>

### 🔍 **Opis Parametrów:**

- **`<metoda>`**: Tutaj należy wpisać metodę crashu. Spis metod crash znajdziesz pod komendą **`,crashhelp`**. 📚
  
- **`<ilość pakietów>`**: Tutaj należy wpisać, ile pakietów ma zostać wysłanych (zależy to od metody oraz rangi, jaką posiadasz). 📦

- **`<window/slot/place>`**: Tutaj należy wpisać jeden z tych pakietów Minecraft. Zaleca się użyć **`WINDOW`**, ponieważ jest to uniwersalny pakiet. **`PLACE`** działa tylko na wersjach **1.8-1.12**. ⚙️

## ❗ **Dodatkowe Informacje:**

Pod komendą **`,crashhelp`** znajdziesz również zalecenia dotyczące ilości pakietów oraz na jakie wersje działa dana metoda crash. 🛠️

## 🤖 **Zalecenia:**

- **Do crashowania zalecane są boty!** Im więcej botów, tym lepiej. 
- Serwery opierają się na wątkach **Netty**. Większość metod w **ttProxy** laguje te wątki.
  
### 🧑‍🤝‍🧑 **Dlaczego Boty Są Ważne?**

- Jeśli crashujesz bez botów, czyli ze swojej sesji, zlagujesz tylko ten wątek Netty, na którym się znajdujesz. 
- Inne wątki, na których są inni gracze, nie będą miały laga. 😬
  
**Zalecenie**: Używając botów, sprawisz, że co najmniej 1 bot wejdzie na każdy wątek Netty serwera (domyślnie serwer ma ich 4). 🏗️

### 📈 **Efekt Crashowania:**

- Im więcej botów, tym więcej wątków Netty się zlaguje, co sprawia, że crash będzie mocniejszy, a efekt lepszy. 🚀
- Crashując z botów, to właśnie one wysyłają wszystkie pakiety, a Ty odczuwasz tylko realny lag serwera (zakładając, że uda się zlagować serwer). 

### ⚠️ **Crashowanie Bez Botów:**

- Jeśli crashujesz bez botów, to Ty wysyłasz pakiety, przez co serwer może zlagować **Twoją sesję**. 
- Będzie Ci się wydawało, że serwer ma laga, lub uda Ci się zlagować wątek, na którym będziesz, co faktycznie sprawi, że ten lag serwera będzie odczuwalny. 

---

### 🎲 **Uwaga:**

Może się zdarzyć, że wykonasz crasha bez botów i ani Ty, ani serwer nie będziecie mieli laga. Tak również się może zdarzyć. 🤷‍♂️

---

### 💡 **Podsumowanie:**

- Zawsze preferuj używanie botów do crashowania.
- Zapoznaj się z komendą **`,crashhelp`** dla pełnych informacji na temat metod i rekomendacji. 
- Pamiętaj o potencjalnych konsekwencjach crashowania. ⚠️


# 🛡️ Obejście Captcha

Aby włączyć i skonfigurować obejście captchy na serwerze, należy wpisać komendę **`,captcha`**. 🖥️

## 📜 **Panel Multicaptcha**

Po wpisaniu tej komendy wyświetli się panel zarządzania captcha, zwany **Multicaptcha**. Ten panel umożliwia skonfigurowanie od 1 do 4 różnych bypassów. 🔧

### 💡 **Cechy Panelu:**
- Włączenie i konfiguracja jednej lub więcej captch, jeśli dany serwer posiada ich kilka.
- Bypassy captcha tworzymy w kolejności, w jakiej są na serwerze. 

#### 🗒️ **Przykład:**
Załóżmy, że serwer ma jedną captchę. Klikamy w **Captcha #1**, a następnie otwiera się GUI konfiguracyjne.

## 🛠️ **Dostępne Obejścia Captcha:**
- Na chacie 🗨️
- Na actionbarze 📊
- Na title 🎮
- Na bossbarze 👑
- Na mapie 🗺️
- Na itemframe (ramce) 🖼️
- W GUI 📋

### 🔧 **Konfiguracja Bypassów:**

#### 1. **Bypass Chat / Title / Bossbar**
Obejścia na chacie, actionbarze, title i bossbarze mają identyczne możliwości konfiguracji. Poniższy opis dotyczy wszystkich wymienionych.

- Po wpisaniu **`,captcha`** kliknij w interesujący Cię rodzaj obejścia. 
- Dla przykładu, wybierzemy obejście captchy na chacie.

#### 🖱️ **Wybór Obejścia:**
- Kliknij w item opisany jako **"Captcha Chat"**. Zostanie on podświetlony, co oznacza, że został "wybrany". 
- Domyślnie obejście jest ustawione na **AUTO**. Możesz kliknąć na ten item drugi raz, aby otworzyć menu z wyborem rodzaju wykrywania captchy:
  - **AUTO**: Automatyczne wyszukiwanie captchy.
  - **MANUAL**: Konfiguracja i zaznaczanie pozycji captchy.

### 📝 **Manualna Konfiguracja:**

Jeśli wybierzesz opcję **MANUAL** i najedziesz myszką na item, wyświetli Ci się konfigurator, w którym należy ustawić pewne rzeczy.

#### 📏 **Ustawienie SŁOWA:**
- Zacznij od ustawienia SŁOWA, od którego będzie liczona pozycja captchy. 
- Wybierz dowolne słowo z wiadomości, w której znajduje się captcha, aby obejście mogło łatwo znaleźć kod captcha.

#### 🖊️ **Jak Ustawić Słowo:**
- Kliknij prawym przyciskiem myszy, a następnie wpisz na chacie wybrane przez nas słowo, od którego będziemy wyznaczać pozycję captchy.

### 📍 **Ustawienie Pozycji Captchy:**
- Po ustawieniu słowa, policz w jakiej odległości od wybranego słowa znajduje się kod captcha.
  
#### 🧮 **Przykład:**
- Jeśli wiadomość brzmi: **„Przepisz kod captcha wpisując na chacie 729463”**, a wykrywane słowo to **„chacie”**, ustaw pozycję captcha na **1** (ponieważ kod captcha jest tuż po słowie „chacie”).

#### 💡 **Jak Ustawić Pozycję:**
- Pozycję captchy ustawia się poprzez klikanie lewego przycisku myszy. 
  - Każde kliknięcie to +1 pozycji, a 1 pozycja to 1 słowo w wiadomości.
  
#### 🔄 **Inny Przykład:**
- Ustawiając wykrywane słowo jako **„Przepisz”**, ustaw pozycję captchy na **6**, ponieważ między słowem "Przepisz" a captchą jest 5 słów, a captcha jest szóstym.

### 🏆 **Rekomendacja:**
Osobiście polecam ustawiać wykrywanie słowa jak najbliżej kodu captchy, by uniknąć trudności w wyznaczaniu pozycji kodu. 🎯

---

### 📝 **Podsumowanie:**
- Aby skonfigurować obejście captcha, użyj komendy **`,captcha`**.
- Możesz dostosować obejścia do swoich potrzeb, a konfiguracja jest intuicyjna.
- Dobrze dobrane słowo i pozycja znacznie ułatwią działanie bypassu. 🥳


# 🗺️ Bypass Map & Itemframe

Konfiguracja bypassu dla **mapy** oraz **itemframe** jest prawie identyczna, dlatego ten poradnik opisuje możliwości oraz konfigurację w jednym punkcie. ⚙️

## 🛠️ **Konfiguracja Bypassu**

### 1. **Bypass Map**
Klikając w opcję **MAP**, otworzy się GUI, w którym należy wybrać lub ustawić pozycję kodu captcha oraz sposób rozwiązania kodu captcha. 🖱️

### 2. **Bypass Itemframe**
Klikając w opcję **ITEMFRAME**, nie otworzy się GUI, lecz informacja, że najpierw trzeba wejść na serwer, którego dotyczy captcha, a następnie poczekać, aż obrazek się pobierze. 📥

#### 📷 **Pobieranie Obrazka:**
Gdy obrazek dla itemframe zostanie pobrany, wtedy będzie można przystąpić do konfiguracji bypassu. 

## ✨ **Zaznaczanie Pozycji Captchy:**

Jeśli chodzi o zaznaczanie pozycji captchy, mamy do wyboru:

- **Map Full**: Czyli cały obrazek 🌍
- **Map Top**: Górna część obrazka 🌄
- **Map Mid**: Środkowa część obrazka 🏞️
- **Map Bottom**: Dolna część obrazka 🌊
- **Map Custom**: Ręczne ustawianie pozycji captcha ✏️

Opcje **full/top/mid/bottom** nie wymagają dodatkowej konfiguracji — są to gotowe pozycje. 

### 👁️ **Podgląd Pozycji:**
Można wyświetlić, jak wygląda zaznaczone pole, klikając lewy przycisk myszy.

#### 🖼️ **Map Custom**
W przypadku opcji **Map Custom**, można w zaawansowany sposób ustawić dokładne pole pozycji captcha na mapie oraz itemframe.

- Klikając prawym przyciskiem myszy, otwieramy GUI, gdzie znajduje się intuicyjny system zaznaczania pozycji captcha na obrazku.
- Ustawiamy wielkość poprzez klikanie w przeciwległe rogi pola. 

#### 📐 **Wielkość Operacyjna:**
Wielkość całego pola, na którym możemy operować, to **9x9 slotów**.

#### 🔍 **Przycisk "Preview":**
W prawym dolnym rogu znajduje się przycisk **"Preview"**, po którego kliknięciu pokazuje się nasze zaznaczone pole na mapie w ręce, dzięki czemu mamy porównanie i widzimy, jakie dokładnie pole będzie dekodowane pod względem szukania kodu captcha.

### 🗺️ **Wybór Wymiarów:**
Obok przycisku **"Preview"** jest opcja **"Type the dimension manually"**. Po kliknięciu tej opcji mamy możliwość ustawienia pozycji captcha na mapie, wpisując odpowiednie wartości, takie jak np. koordynaty mapy.

- **Wielkość mapy** to **128x128**, gdzie **Y** to wysokość, a **X** to szerokość.

#### 🔄 **Dodatkowe Opcje:**
- **Reset**: Resetuje zaznaczone pole do domyślnego. 🔄
- **Back**: Cofnięcie się do poprzedniego GUI. 🔙

### 🧐 **Ciekawostka:**
W przypadku konfigurowania customowej pozycji captchy na **itemframe**, również odbywa się to na mapie trzymanej w ręce. Działa to na zasadzie pobrania obrazka itemframe z serwera, a następnie jego przeskalowania i umieszczenia w formie podglądu na mapie w ręce. Dzięki temu jesteś w stanie dokładnie ustawić pozycję captcha tam, gdzie jest kod. 

## 📜 **Rozwiązywanie Kodu Captcha**

Gdy zaznaczenie pozycji captcha mamy za sobą, czas przejść do sposobów rozwiązywania kodu. Do wyboru są 3 opcje:

1. **Map Simple Decoder**: Prosty algorytm rozpoznawania captcha. 📈
2. **Map Manual Decoder**: Ręczne rozwiązywanie kodu captcha. ✍️
3. **Map Api Decoder**: Zewnętrzny solver captcha działający poprzez API. 🔌

### 1. **Map Simple Decoder**
Nadaje się do captch, gdzie literki są proste, czcionka jest "normalna" i brak jakichkolwiek specjalnych filtrów, przekrzywień itp. 

**Przykład:**
- Captcha z pluginu JPremium (ta z tarczą na środku). 
- [Link podglądowy](https://proxy.spigotmc.org/69071e2fd1f1244f71b3daecf4d8f647fca3debf?url=https%3A%2F%2Fraw.githubuse rcontent.com%2FJakubson%2FJPremiumCleared%2Fmaster%2Fimages%2Fimage1.png)

### 2. **Map Manual Decoder**
Opcja ręcznego przepisywania captchy przez bota. 🤖

- Captcha, którą bot otrzyma, zostanie wyświetlona, a naszym zadaniem jest przepisanie kodu z tej captchy na chat.
- System został dopracowany, więc nie powinno być problemów z przepisywaniem captchy.

#### ⏰ **Zalecenia:**
- Jeśli serwer ma czas na przepisanie captchy, zaleca się ustawić większy delay łączenia botów (np. powyżej 2000), aby mieć czas na przepisywanie captchy. 

### 3. **Map Api Decoder**
To najlepsza opcja, która niestety jest dodatkowo odpłatna. 💰

- Cennik znajduje się na prywatnym Discordzie.
- Opcja ta polega na tym, że bot po otrzymaniu captchy, wysyła ją do solvera, a ten w ciągu kilku sekund poda kod captcha.

#### ⚠️ **Uwaga:**
Jeżeli kod captcha jest trudny do rozkodowania, to zmniejsza się szansa, że zdekodowany kod captcha będzie poprawny.

### 📊 **Użycie Solverów:**
Do Api decodera przypisana jest liczba użyć solvera. Kupując np. **10000 użyć**, można rozwiązać aż **10000 captchy** (zakładając, że wszystkie zdekodowane kody captcha będą poprawne). 

---

### 🏁 **Podsumowanie:**
- Konfiguracja bypassu dla mapy oraz itemframe jest intuicyjna i łatwa do wykonania.
- Różne metody rozwiązania captcha dostosowują się do potrzeb użytkownika, a każda z opcji ma swoje zalety i wady. 


# 🖥️ Bypass GUI

Bypass captchy w **GUI** jest dosyć prosty i nie wymaga specjalnej konfiguracji, ponieważ całość jest w pełni automatyczna. 🌟

## 🛠️ **Wybór Rodzaju Captchy**

Jedynie trzeba wybrać rodzaj captchy w GUI. Do wyboru są na tę chwilę 4 rodzaje:

1. **Items GUI Name**: 
   - Kliknięcie itemu, który jest opisany w ramce GUI. 🏷️

2. **Items Min Stack**: 
   - Kliknięcie itemu, który ma najmniejszą wartość w stacku. 📉

3. **Items Max Stack**: 
   - Kliknięcie itemu, który ma największą wartość w stacku. 📈

4. **Items Other Stack**: 
   - Kliknięcie itemu, który różni się od innych. 🔄

---

### 🚀 **Podsumowanie**
Proces bypassu captchy w GUI jest szybki i intuicyjny, co pozwala na bezproblemowe przejście przez system. Wystarczy wybrać odpowiednią opcję, a resztą zajmie się automatyzacja! 🎉


# ⚙️ Konfiguracja Wysyłanej Komendy

Aby skonfigurować, jak ma wyglądać wiadomość z captchą wysyłaną przez bota, należy wejść w opcje **"Configure"**. 🛠️

## 🖥️ **Menu Konfiguracyjne**

Po kliknięciu otworzy się menu z całym panelem konfiguracyjnym. Mamy tam do dyspozycji tak zwane **narzędzia**, które są opisane (niebieska wełna). 🔵

Nad nimi znajdują się puste sloty, w które należy wkładać te **"narzędzia"** (w barrier blocki). 🧱

Cała konfiguracja polega na tym, aby z dostępnych narzędzi utworzyć komendę, którą będą wpisywać boty. Do dyspozycji są takie narzędzia jak:

- `/register` - czyli /register 📋
- **Custom Command** - Własna komenda ✍️
- **Nickname** - Nick bota 👤
- **Password** - Hasło 🔑
- **Code from Captcha** - Pobrany kod captcha 🔓

---

## 📖 **Przykład 1: Stworzenie Komendy `/register haslo haslo <kod captcha>`**

Aby utworzyć sekwencję komendy `/register haslo haslo <kod captcha>`, należy:

1. Kliknąć w item o nazwie `/register`, a następnie kliknąć na **pierwszy barrier block** od lewej strony. ➡️
2. Następnie kliknąć na item o nazwie **Password** i kliknąć na **drugi barrier block** od lewej strony. 🔒
3. Powtórzyć czynność i na **trzeci slot** również dać item o nazwie **Password**. 📜
4. Na **czwarty slot** należy dać item o nazwie **Code From Captcha**. 📥

Aby zapisać całość, należy kliknąć **czerwoną pochodnię** o nazwie **"Save the sequence"**. 🔴

Od tej pory boty będą wpisywać: 
/register haslo haslo <kod captcha>

---

## 📖 **Przykład 2: Stworzenie Komendy `/captcha <kod captcha>`**

Na start należy:

1. Kliknąć w item o nazwie **"Custom Command"**, a następnie wpisać na chacie słowo `/captcha`, a potem kliknąć **Enter**. 🔑
2. Wtedy otworzy się z powrotem menu konfiguracji. Należy kliknąć na **pierwszy barrier block**, aby umieścić w nim to słowo. 📬
3. Na **drugi barrier block** należy dać item o nazwie **"Code from Captcha"** w identyczny sposób jak w poprzednim przykładzie (tym razem na **drugi barrier block** od lewej strony). 📊
4. Na koniec całość zapisujemy klikając w **czerwoną pochodnię** o nazwie **"Save the sequence"**. 🔴

---

## 📌 **Dodatkowe Informacje**

- Aby zmienić hasło wpisywane przez boty podczas używania captcha, należy wpisać komendę `,register settings` i tam zmienić typ hasła na inny, np. **randomowe**. 🔄
- Obejście captcha jest częściowo kompatybilne z funkcją `,autoregister`, dzięki czemu te funkcje nie powinny ze sobą kolidować, gdy będą włączone obie na raz. ⚖️
- Gdy serwer będzie miał captche, a komenda do wpisania to `/register haslo haslo captcha`, to z automatu **autoregister** się wyłączy. 🚫
- Natomiast w przypadku, gdy obejścia captcha będzie skonfigurowana jako `/captcha <captcha>` lub coś podobnego, to wtedy **bypass captcha** rozwiąże captcha, a **autoregister** zarejestruje w zależności od kolejności. 🔄


# 📬 #10 Massmsg / Masscmd

## 📩 **Massmsg**

Komenda `,massmsg` służy do wysyłania wiadomości `/msg` do **wszystkich graczy** na serwerze. 

### 🛠️ **Wzór Komendy:**
,massmsg <delay/stop> <infinity [true/false]> <bots [true/false]> <wiadomość>

### 📋 **Opis Argumentów:**

- **`<delay/stop>`**: 
  - Wpisz wartość (co ile milisekund ma być wysyłana wiadomość) lub słowo **stop**, jeżeli chcesz zatrzymać wysyłanie (wtedy pozostałych argumentów nie uzupełniamy). ⏱️
  
- **`<infinity>`**: 
  - Wpisz **true**, jeżeli ma wysyłać w nieskończoność, lub **false**, jeżeli ma wysłać raz. 🔄

- **`<bots>`**: 
  - Wpisz **true**, jeżeli do wysyłania wiadomości mają zostać wykorzystane boty, lub **false**, jeżeli wiadomości mają być wysyłane przez nas. 🤖

- **`<wiadomość>`**: 
  - Wpisz treść wiadomości. Dodatkowo, aby umożliwić obchodzenie zabezpieczeń antyspam, w dowolnym miejscu możesz wstawić `[r]` oraz `[n]`, co oznacza **randomowe litery** oraz **liczby**. Można także ustawić ich ilość w taki sposób: 
  - **`[r:ilość]`** lub **`[n:ilość]`**, np. `[r:3]` `[n:6]`. 
  - Można to wstawiać w dowolnym miejscu i w dowolnych ilościach. 🎉

---

## 💬 **Masscmd**

Dzięki komendzie `,masscmd` można wysłać masowo **dowolną komendę** do wszystkich graczy na serwerze. 

### 🛠️ **Wzór Komendy:**
,masscmd <delay/stop> <bots [true/false]> <single/multi/false> <command>

### 📋 **Opis Argumentów:**

- **`<delay/stop>`**: 
  - Wpisz wartość (co ile milisekund ma być wysyłana komenda) lub słowo **stop**, jeżeli chcesz zatrzymać wysyłanie (wtedy pozostałych argumentów nie uzupełniamy). ⏱️

- **`<bots>`**: 
  - Wpisz **true**, jeżeli do wysyłania komendy mają zostać wykorzystane boty, lub **false**, jeżeli komendy mają być wysyłane przez nas. 🤖

- **`<single/multi/false>`**: 
  - Opcje **single** oraz **multi** są dla botów, natomiast **false** wpisujemy, gdy nie używamy botów do tej funkcji. 

  - **Single**: 
    - Każdy pojedynczy bot wyśle **jedną komendę** do jednego unikalnego gracza. 
    - Przykład: Mamy 30 botów i 50 graczy. Używając opcji **single** oraz komendy `/tpa nick`, 30 graczy otrzyma prośbę o teleportację od jednego losowego bota. 📩

  - **Multi**: 
    - Każdy gracz na serwerze otrzyma **zapytanie** od wszystkich botów. 
    - Przykład: Jeśli użyjemy opcji **multi**, wszystkie boty wyślą `/komenda nick` do gracza nr 1, nr 2, nr 3 itd. 🚀

- **`<command>`**: 
  - Tutaj wpisujemy `/komenda`, a w dowolnym miejscu dodajemy **@players**. 
  - **@players** to miejsce, w którym będą znajdowały się nicki graczy. 👤

### 📖 **Przykład:**
,masscmd 3000 true single /tpa @players

- W tym przypadku:
  - **bot_1** wyśle `/tpa gracz1`,
  - **bot_2** wyśle `/tpa gracz2`,
  - **bot_3** wyśle `/tpa gracz3`. 🔄

---

Mam nadzieję, że jest to zrozumiałe, jak to działa! Jeśli masz jakieś pytania, nie wahaj się pytać! 😊


# 🔗 #11 Łączenie z Kont Premium

Funkcja `,accountmc` umożliwia dodanie jednego lub kilku kont premium, a następnie łączenie się z nimi na serwerach premium, np. **hypixel.net**. 🎮

## 🛠️ **Dostępne Komendy:**

1. **``,accountmc list``** 
   - Wyświetla listę dodanych kont. 📋

2. **``,accountmc login <token> <thealtening/mceasy>``** 
   - Dodaje konto za pomocą **The Altening** lub **MC Easy**. 🔑

3. **``,accountmc login <email> <password> <proxy>``** 
   - Dodaje konto za pomocą emaila i hasła. 📧🔒

---

## ⚠️ **Uwaga dotycząca Dwuetapowej Weryfikacji:**

Przy próbie dodania konta premium za pomocą emaila i hasła, może pojawić się informacja, że konto ma **autoryzację dwuskładnikową**. 

To oznacza, że musisz:

1. Zalogować się na swoje konto Microsoft w przeglądarce. 🌐
2. Potwierdzić, że to Ty logujesz się do konta.

Aby bezpośrednio przejść do panelu bezpieczeństwa Microsoft, kliknij w link, który wyświetlił się na czacie **ttProxy** podczas próby logowania, poniżej czerwonego napisu. 🔴

### 🔄 **Po potwierdzeniu logowania:**

1. Wróć do **ttProxy**. 
2. Kliknij na przycisk **"click here"** na czacie, aby automatycznie ponowić próbę logowania z tego samego IP. 🔄

Po tych krokach, konto powinno zostać pomyślnie dodane. 🎉

---

## 🔑 **Używanie Konta Premium do Łączenia się z Serwerami:**

1. Aby móc użyć konta premium, wpisz **`,accountmc list`**, a następnie kliknij **select**. 
   - Może się zdarzyć, że konto będzie automatycznie wybrane i nie będzie możliwości kliknięcia **select**. ⚙️

2. Kiedy konto jest dodane i wybrane, możesz użyć go do połączenia się. 🌐

3. Aby to zrobić, wpisz słowo **`[account]`** w argumencie `<nick>` w komendzie **`,connect`**. 

### 📞 **Przykład:**
,connect [account]

Po użyciu tego polecenia, powinno nastąpić połączenie z dodanym nickiem premium. 

**Opcja `[account]` dotyczy również kont dodanych przez The Altening i MC Easy.** 🤖

---

Jeśli masz pytania lub potrzebujesz dodatkowych informacji, śmiało pytaj! 😊

# 📜 #12 Własna Lista Nicków

Aby dodać swoją własną listę nicków, wykonaj poniższe kroki! 📝✨

## 1. Utworzenie Listy Nicków:

1. Wejdź na stronę **[Pastebin](https://pastebin.com)**. 🌐
2. Utwórz nową listę nicków w formacie: 
Nick1
Nick2
Nick3

- **Każdy nick musi być w osobnej linii!** 🔤

3. Ustaw listę jako **publiczną** lub **niepubliczną** (pamiętaj, aby nie ustawiać jej jako prywatną!). 🔒

---

## 2. Skopiowanie ID Pastebina:

1. Po stworzeniu listy, skopiuj **ID** pastebina z linku. 
- Chodzi o tę końcówkę po **`https://pastebin.com/`**. 📋

---

## 3. Dodawanie Listy do Bota:

1. Wklej skopiowane ID do komendy: 
,addproxy add <ID>

- Zastąp **`<ID>`** skopiowanym ID (bez nawiasów). 🚀

---

## 4. Wybór Dodanej Listy:

1. Po dodaniu listy, wpisz:
,ownnicknames list

2. Kliknij **select** przy dodanej liście. ✅

---

## 5. Używanie Nicków:

Aby użyć tych nicków w komendzie, wpisz słowo **`[own]`** w argumencie `<nick>` w komendzie **`,connect`** lub **`,connectbot`**. 🔗🤖

### 📞 **Przykład:**
,connect [own]

Po wykonaniu tych kroków, Twoje nicki będą gotowe do użycia! 🎉 Jeśli masz pytania, śmiało pytaj! 😊


# 🛠️ #13 Własna Lista Proxy

Aby dodać swoją własną listę adresów proxy, wykonaj poniższe kroki! 🌍✨

## 1. Utworzenie Listy Proxy:

1. Wejdź na stronę **[Pastebin](https://pastebin.com)**. 🌐
2. Wrzucić listę proxy w formacie: 
ip
lub ip:port:login

- Akceptowane rodzaje proxy:
  - **HTTP/HTTPS** 🌐
  - **SOCKS4/5** 🔒
- **Uwaga:** Nie mieszaj proxy HTTP z SOCKS w jednej liście! ⚠️

3. Ustaw pastebin jako **unlisted** i zaznacz opcję **never** (nigdy) dla wygaszenia. 🛑

---

## 2. Skopiowanie ID Pastebina:

1. Po kliknięciu przycisku **"create new paste"**, skopiuj **ID** z linku. 
- To, co znajduje się po **`https://pastebin.com/`**. 📋

---

## 3. Dodawanie Listy Proxy do Bota:

1. Wklej skopiowane ID do komendy:
,ownproxy add <ID>

- Zastąp **`<ID>`** skopiowanym ID (bez nawiasów). 🚀

2. Po wpisaniu tej komendy na chacie, pojawi się zapytanie o typ proxy.
- Do wyboru jest **HTTP** lub **SOCKS**. 

3. Wybierz odpowiedni typ proxy:
- Kliknij **SOCKS**, jeśli dodałeś SOCKS. 
- Kliknij **HTTP**, jeśli dodałeś HTTP. ✅

4. Po wybraniu typu proxy, na chacie pojawi się informacja, że lista proxy została dodana. 🎉

---

## 4. Wybór Listy Proxy:

1. Aby wybrać listę proxy, wpisz:
,ownproxy list

- Wyświetli się lista wszystkich twoich proxy. 📜

2. Załóżmy, że dodajesz proxy po raz pierwszy. Twoja lista będzie miała nazwę **ID:1**. 

3. Przy tej liście znajdują się przyciski:
- **Select**: zaznacz i wybierz listę proxy, którą będziesz używać. ✔️
- **Save**: jednorazowy przycisk, po jego kliknięciu lista ta zostanie zapisana na zawsze. 💾
- **Remove**: bezpowrotne usunięcie listy proxy. ❌

4. **Uwaga:** Wybranie jednej listy, a następnie innej, nie sprawi, że pierwsza przestanie być używana. Możesz mieć wybrane dwie listy na raz! 🔄
- Aby zrezygnować z pierwszej, odkliknij **select** przy ID, którego nie chcesz mieć wybranego.

---

## 5. Użycie Własnych Proxy:

Aby użyć własnych proxy w komendzie, wpisz słowo **`own`** w argumencie `<proxy>` w komendzie **`,connect`** lub **`,connectbot`**. 🔗🤖

### 📞 **Przykład:**
,connect <nick> <own>

Teraz twoje proxy są gotowe do użycia! 🚀 Jeśli masz pytania, śmiało pytaj! 😊
