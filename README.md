# urbandog
sito web di  urban dog
# Urban Dog School – README tecnico per Codex

Questo file README è destinato a Codex o a qualsiasi sviluppatore che voglia completare e pubblicare il sito web per "Urban Dog School" a partire dai file `index.html` e `style.css` presenti nella repository.

---

## ✅ Obiettivo

Realizzare un sito web **mobile-friendly**, **esteticamente accattivante**, **responsive** e pronto per la pubblicazione, dedicato al progetto cinofilo **Urban Dog School** fondato da Francesco Corsaro.

---

## 📁 Struttura Attuale della Repository

```
urban_dog_school/
├── index.html          # Pagina HTML principale
├── style.css           # Foglio di stile CSS
└── images/             # Cartella da popolarsi con immagini reali
    ├── img1.jpg        # Miele sul divano
    ├── img2.jpg        # Passeggiata nel bosco
    └── img3.jpg        # Cane nel locale
```

---

## 🎯 Prompt generali per sviluppo frontend

Questi prompt guidano lo sviluppo del sito basandosi sull'identità e sugli obiettivi di Urban Dog School.

### 1. 🖼️ Hero Section
**Prompt:**
> Crea un header mobile-friendly con logo e slogan. Inserisci uno sfondo chiaro e un bottone WhatsApp verde. Il testo centrale deve comunicare: “Educazione Urbana per Cani Felici e Padroni Sereni”.

### 2. 📱 Responsive Design
**Prompt:**
> Ottimizza tutti gli elementi per mobile. Usa media queries per gestire padding, font size e spaziature. Tutti gli elementi devono scalare perfettamente su schermi da 375px a 1200px.

### 3. 🎨 Tema visivo
**Prompt:**
> Applica una palette ispirata a blu notte (#003366), bianco panna (#fefefe), verde WhatsApp (#25D366) e dettagli giallo sabbia (#FFD700). Font consigliato: Poppins o Arial.

### 4. 📦 Sezioni richieste
- Hero con call-to-action WhatsApp
- “Chi siamo” con breve bio e foto
- “Servizi” con elenco (puppy training, educazione urbana, riabilitazione)
- “Gallery” con immagini vere
- “Contattaci” con form email (già presente) e link WhatsApp
- Footer con copyright

---

## 🛠️ Cose da fare (To Do List per Codex)

1. ✅ Migliorare struttura mobile con Flexbox e Media Queries
2. ✅ Inserire sezione “Chi siamo” sotto Hero con bio di Francesco Corsaro (psicologo, educatore cinofilo, fondatore del progetto)
3. ✅ Ottimizzare galleria immagini con `<picture>` o `<img>` responsive
4. ✅ Applicare design coerente (colori, font, bordi, pulsanti, spaziature)
5. ✅ Aggiungere favicon
6. ✅ Integrare icone (zampa, guinzaglio, osso) usando librerie come Font Awesome
7. ✅ Validare HTML/CSS W3C
8. ✅ Preparare versione light/dark se possibile

---

## 💬 Prompt extra per ChatGPT/Codex

> “Crea un layout responsive per un sito web cinofilo. Il sito deve avere un aspetto urbano e moderno. Le sezioni devono includere: Hero con CTA WhatsApp, Chi siamo con bio breve, Servizi con elenco a icone, Gallery con foto reali, e Contatti con modulo form e footer. I colori devono essere navy, sabbia e verde. Deve essere mobile-first.”

---

## 🔗 Contatti

Per info dirette o test finali, il contatto WhatsApp predefinito è:
📱 [https://wa.me/393485686702](https://wa.me/393485686702)
https://wa.me/393485686702?text=Ciao%20Francesco!%20Ho%20visto%20il%20sito%20Urban%20Dog%20School%20e%20vorrei%20saperne%20di%20pi%C3%B9%20sui%20tuoi%20servizi%20per%20l%E2%80%99educazione%20del%20mio%20cane.


Email form invia a:
📧 francesco.corsaro.psi@gmail.com
mailto:francesco.corsaro.psi@gmail.com?subject=Contatto%20dal%20sito%20Urban%20Dog%20School&body=Ciao%20Francesco%2C%20ti%20contatto%20dal%20sito.%20Vorrei%20chiederti%20informazioni%20su...

---

## 📤 Deployment suggeriti

- [Netlify Drop](https://app.netlify.com/drop)
- GitHub Pages
- Vercel
- Altervista FTP (versione statica)

---

## 📎 Note finali

Le immagini vanno salvate nella cartella `images/` e linkate nel codice come `images/nome.jpg`.

Assicurati che tutto sia:
- accessibile (testi alternativi immagini)
- ben bilanciato nei margini
- con buona leggibilità su sfondi chiari



 Codice di esempio (Hero Banner Elementor personalizzato)
html
Copia
Modifica
<section style="background-image: url('/img/miele-hero.jpg'); padding: 100px 20px; text-align: center; background-size: cover;">
  <h1 style="color: white; font-size: 32px;">Educazione urbana per cani felici<br> e padroni sereni</h1>
  <a href="#prenota" style="background-color: #FFD700; color: #001F3F; padding: 14px 28px; border-radius: 8px; font-weight: bold; display: inline-block; margin-top: 20px;">Prenota una consulenza gratuita</a>
</section>


JS Interattivi
“Fammi uno script che apre un popup con un consiglio cinofilo casuale ogni volta che l’utente entra nella pagina”
Buon lavoro 🐶💻


PHP per WordPress
“Fammi un codice PHP da inserire in functions.php per aggiungere un pulsante WhatsApp in fondo alla pagina mobile”

Pagine da creare:

Home

Chi siamo

Servizi (una pagina con anchor link o tre sottopagine)

Metodo

Contatti

Prenota

Blog (WordPress la crea in automatico)

Come farlo:

Vai su "Pagine > Aggiungi nuova"

Titola la pagina (es. “Home”), clicca “Modifica con Elementor”

Inserisci sezioni (hero image, titoli, bottoni, testo, immagini)


🌐 SITO WEB – URBAN DOG SCHOOL
✅ 1. OBIETTIVI DEL SITO
Presentare professionalmente Urban Dog School come punto di riferimento per l’educazione cinofila urbana a Catania.

Offrire una panoramica chiara dei servizi: puppy training, educazione base, riabilitazione comportamentale.

Fungere da canale di contatto diretto per richieste, iscrizioni e appuntamenti.

Costruire fiducia nel brand con testimonianze, contenuti educativi e immagini d’impatto.

🧩 2. STRUTTURA DEL SITO (SITEMAP)
java
Copia
Modifica
/
├── Home
├── Chi siamo
├── Servizi
│   ├── Puppy Training
│   ├── Educazione Base
│   ├── Riabilitazione Comportamentale
├── Metodo
├── Blog
├── Contatti
├── Prenota
└── Area Clienti (Futuro)
🎨 3. DESIGN & USER EXPERIENCE
Stile visivo:

Tema urban + naturale

Colori principali: blu notte (#001F3F), giallo sabbia (#FFD700), bianco panna

Font: moderno e leggibile → es. Poppins o Montserrat

Immagini vere di Miele in azione: salvataggio, gioco, addestramento urbano

Logo: cane stilizzato seduto accanto a un palazzo con coda a forma di cuore

Wireframe logico (versione desktop):

csharp
Copia
Modifica
[Logo]     [Home] [Servizi] [Metodo] [Chi siamo] [Blog] [Contatti] [Prenota]

-------------------------------------------------------------
| HERO IMAGE con claim forte: "Educazione urbana per cani felici e padroni sereni" |
| Bottone: [Prenota una consulenza gratuita]                                        |
-------------------------------------------------------------

[Sezione 1: Chi siamo]
Foto di Miele e Francesco + descrizione breve e autentica

[Sezione 2: Servizi]
Icone e box sintetici per ogni servizio con bottone "Scopri di più"

[Sezione 3: Metodo]
Descrizione del metodo Urban: comunicazione, rinforzo, relazione

[Sezione 4: Perché sceglierci]
Checklist punti di forza + testimonianze brevi + badge qualità

[Sezione 5: Contattaci]
Modulo contatto rapido + numero WhatsApp + indirizzo e mappa

[Footer]
Link rapidi | Privacy | Instagram | Mail | Logo
📄 4. CONTENUTI DELLE PAGINE PRINCIPALI
🏠 Home
Urban Dog School è la tua scuola cinofila urbana a Catania. Addestriamo cani e formiamo umani per vivere insieme in armonia nel contesto cittadino. Passeggiate tranquille, comandi affidabili, gestione degli impulsi: tutto è possibile quando comunicazione e fiducia sono al centro del rapporto.

📘 Chi siamo
Siamo un’associazione sportiva senza scopo di lucro nata per migliorare la convivenza uomo-cane in ambiente urbano. Fondata da Francesco Corsaro, psicologo e istruttore cinofilo, Urban Dog School fonde l’esperienza in psicologia comportamentale con tecniche moderne di educazione canina.

🐾 Servizi
1. Puppy Training

Percorso educativo dai 2 ai 6 mesi

Socializzazione urbana, morsi, bisogni, comandi base

2. Educazione Base

Richiamo, condotta al guinzaglio, gestione emozioni

Adatto a cuccioli, adolescenti e cani adulti

3. Riabilitazione Comportamentale

Paure, aggressività, iperattività

Protocollo personalizzato in base al caso

🔬 Metodo
Usiamo un approccio moderno e scientifico, basato su:

Rinforzi personalizzati (con app in sviluppo!)

Relazione empatica cane-conduttore

Educazione nel contesto reale (pizzerie, marciapiedi, parchi)

Mentalità positiva, niente coercizione

Esperienza integrata con psicologia comportamentale

📰 Blog
Articoli brevi, utili e concreti:

“Come scegliere il rinforzo giusto per il tuo cane”

“Cosa fare se il tuo cane abbaia a tutti per strada”

“Come abbiamo insegnato a Miele a ignorare i cani aggressivi”

📞 Contatti
Modulo + WhatsApp link + Instagram
Mappa zona Catania
Possibilità di primo incontro gratuito

📅 Prenota
Calendario con disponibilità
Form prenotazione base (nome, cane, problema, numero)

🛠️ 5. TECNOLOGIE CONSIGLIATE
Area	Tecnologie
CMS / builder	[Francesco friendly] → WordPress + Elementor o Dorik
Hosting	Netlify (statico) oppure SiteGround (WP hosting)
Dominio	urban-dog-school.it (da acquistare)
Analytics	Google Analytics + Facebook Pixel
Email	Gmail personalizzato 
Prenotazione	Calendly integrato / TidyCal / WP Booking Plugin
SEO base	Yoast SEO o RankMath
Responsive Design	Mobile-first con test su dispositivi reali
Modulo contatto	WPForms / Netlify Forms / Tally.so (no codice)


🔖 7. CALL TO ACTION PRINCIPALI
"Prenota una consulenza gratuita" (bottoni ben visibili)

"Contattaci su WhatsApp"

"Segui Miele su Instagram"

"Scopri i nostri servizi"

—
Urban Dog School Web Dev Guidelines
