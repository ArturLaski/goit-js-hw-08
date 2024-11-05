# goit-js-hw-08

## Opis projektu
Projekt ten polega na stworzeniu galerii obrazów, które po kliknięciu wyświetlają pełnowymiarowy obraz w oknie modalnym. Jest to ostatnie zadanie domowe, wymagające stworzenia komponentu galerii z interaktywnym podglądem obrazów.

## Struktura projektu
Projekt składa się z następujących plików i folderów:
- `/css`
  - `styles.css` - Arkusz stylów, który zawiera style dla galerii.
- `/js`
  - `gallery.js` - Skrypt odpowiedzialny za dynamiczne generowanie galerii oraz obsługę zdarzeń kliknięcia.
- `index.html` - Strona główna projektu, która zawiera kontener dla galerii i ładuje style oraz skrypty.
- `README.md` - Dokumentacja projektu

## Wymagania funkcjonalne
1. **Markup galerii**: 
   - W pliku HTML znajduje się element `ul` o klasie `gallery`, który stanowi kontener dla obrazów galerii.

2. **Tablica obrazów**: 
   - Plik `gallery.js` zawiera tablicę `images` z obiektami reprezentującymi elementy galerii, zawierającymi klucze `preview`, `original`, oraz `description`.

3. **Tworzenie markup dla galerii**: 
   - Skrypt `gallery.js` generuje HTML dla każdego obrazu z tablicy `images` i wstawia je do elementu `ul.gallery`. Każdy obraz jest zawarty w tagu `li` i posiada link (`a`) z miniaturką (`img`).

4. **Stylowanie galerii**:
   - Stylowanie galerii odbywa się przy pomocy CSS zawartego w `styles.css`, który ustawia odpowiedni layout oraz inne style.

5. **Delegacja zdarzeń**:
   - Delegacja zdarzeń została zastosowana do nasłuchiwania kliknięć na elementy galerii. Po kliknięciu elementu, link do dużego obrazu jest logowany do konsoli.

6. **Integracja z biblioteką basicLightbox**:
   - Skrypt `gallery.js` korzysta z biblioteki `basicLightbox` do wyświetlania dużych obrazów w oknie modalnym. W `index.html` dodano odpowiednie linki do skryptów biblioteki.

7. **Wyświetlanie dużego obrazu**:
   - Po kliknięciu w miniaturkę, `gallery.js` aktualizuje `src` elementu `img` w oknie modalnym na link do pełnego obrazu i wyświetla go.

## Wymagania techniczne
- Kod musi być sformatowany za pomocą Prettier.
- Nie mogą występować żadne błędy ani ostrzeżenia w konsoli po otwarciu strony.
- Galeria powinna być dynamicznie generowana z tablicy `images` w `gallery.js`.

## Uruchamianie projektu
1. Upewnij się, że wszystkie pliki są odpowiednio umieszczone zgodnie z powyższą strukturą.
2. Otwórz plik `index.html` w przeglądarce, aby zobaczyć działanie galerii.
3. Kliknięcie na miniaturkę powinno otworzyć pełnowymiarowy obraz w oknie modalnym.

## Linki do zasobów
- **basicLightbox**: Biblioteka używana do wyświetlania okna modalnego. Linki do plików CSS i JS dodano w `index.html`.

## Formatowanie kodu za pomocą Prettier
* Aby użyć Prettier, musisz zainstalować go w swoim projekcie, jeśli masz zainstalowany Node.js, za pomocą polecenia:

