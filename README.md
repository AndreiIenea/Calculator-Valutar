#### Descriere cod:
- In acest cod avem secvente de HTML, JavaScript si CSS:
- HTML: In HTML definim structura paginii, incluzand elemente de intrare pentru suma de conversie si valutele de origin, cat si butonul de conversie plus un container pentru a afisa rezultatul.
- CSS: CSS-ul oferă aspectul și stilul paginii, inclusiv aspectul containerului și al butonului, precum și efecte de hover și focus.
- JavaScript: JavaScript-ul gestionează conversia valutară. Atunci când utilizatorul apasă butonul "Converteste", funcția convertCurrency() este apelată. Această funcție preia valorile sumei și valutelor de la utilizator, construiește un URL pentru a efectua o solicitare către un API de conversie valutar, trimite solicitarea folosind fetch(), analizează răspunsul JSON pentru a obține rezultatul conversiei și afișează rezultatul pe pagină.
#### Ce este API? :
-  Application Programming Interface(API) este un set de definiții de sub-programe, protocoale si unelte pentru programarea de aplicații si software. API poate fii folosit pentru sistem web, sisteme de baze de date, biblioteci software, etc.

#### Modificari necesare :
- Trebuie adaucata o cheia API
- Modificarea se face pe linia 103. 
- Exemplu linia 103 : const apiKey='aici cheia API'

#### Link API key:

-[ExchangeRate-API](https://www.exchangerate-api.com/)
