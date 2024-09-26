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
