

DOM exercises

Kom igång
Ladda ner sinus minishop. All din kod ska skrivas i script.js.
I denna övning kommer du få öva på:

Leta reda på saker i DOM och ändra innehåll
Lyssna efter events på olika element
Lägga till ny HTML med JS


DOM Selecta!
![image](https://github.com/user-attachments/assets/a9c89ecb-5759-4d5d-ad7f-cdf17c511f63)
![image](https://github.com/user-attachments/assets/bdbd3c7d-fe4e-488d-841e-29065a241325)


1. Byt namn på första hoodien från Ash till Potato.

    Tips
    använd .innerText

2. Byt namn på Home till Start.
3. Byt namn på Contact till Mail Us.
4. Byt ut informationen om Sinus Hoodie  - Fire.
5. Byt bakgrundsfärg och text på en knapp.

    Tips
    använd el.style.backgroundColor

6. Byt bakgrundsfärg på någon av produkterna.
7. Byt ut adressen på sidan.
8. Byt färg på samtliga <p>.

    Tips
    använd .querySelectorAll()

9. Ändra text på samtliga knappar till add to cart.
10. Lägg till classen active på menyalternativet home.

    Tips
    använd el.classList.add()

11. Ta bort classen logo på logotypen.

    Tips
    använd el.classList.remove()


Add Content
12. Lägg till ett nytt menyalternativ.
13. Lägg till en ny produkt med följande info.



el
beskrivning




img
hoodie-forrest.png


h2
Sinus Hoodie


h3
Forrest


p
Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, dolores.




    Tips
    använd el.insertAdjecentHTML('beforeend',...)


Events
14. Lyssna efter ett klick på logotypen (.logo). När den registrerar ett klick skall du console.log:a "found you!";
15. Lyssna efter klick på samtliga produkter ( <article>). När den registrerar ett klick skall du console.log:a "Hi, Im article Fire / Ash / Water".
