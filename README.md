# 🛒 SmartSpesa

> **Meno strada. Più freschezza. Zero stress.**

SmartSpesa è una web-app mobile-first progettata per rivoluzionare il modo in cui fai la spesa. Non è una semplice "to-do list", ma un vero e proprio **navigatore logistico per i tuoi acquisti**. L'app ordina automaticamente i prodotti in base alla tua posizione GPS e alla tipologia di alimento, generando un itinerario perfetto.

## ✨ Funzionalità Principali (La Magia)

* **🗺️ Routing Intelligente (Distanza):** Grazie al calcolo delle coordinate GPS, i prodotti vengono ordinati dal supermercato più lontano a quello più vicino a te.
* **❄️ Salvataggio Freschi (Temperatura):** I prodotti contrassegnati come "Frigo/Fresco" vengono forzati in fondo alla lista e come ultima tappa del navigatore, per non farli rovinare nel bagagliaio.
* **🧭 Navigatore Multi-Tappa:** Un solo tap sul pulsante "Naviga Tutto" genera automaticamente un percorso Google Maps con fermate intermedie per tutti i negozi della tua lista.
* **🧠 Memoria Statistica:** L'app impara dalle tue abitudini. I prodotti frequenti vengono autocompletati e i 5 più acquistati appaiono in una barra rapida ("One-tap add").
* **👆 Swipe Gestures Native:** Esperienza fluida come un'app iOS/Android. Scorri a destra per spuntare un prodotto, scorri a sinistra (sfondo rosso) per eliminarlo.
* **🔐 Sincronizzazione in Tempo Reale:** Basata su Supabase, permette a più persone della stessa famiglia di vedere la lista aggiornarsi in diretta (Live Updates).

## 🛠️ Stack Tecnologico

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (Zero framework per la massima leggerezza).
* **Backend & Database:** [Supabase](https://supabase.com/) (PostgreSQL per le tabelle, Row Level Security, Auth per il login).
* **Mappe & Geocoding:** API Nominatim (OpenStreetMap) per la ricerca dei negozi, Google Maps per la navigazione in auto.
* **Hosting:** Pubblicazione automatica tramite [Netlify](https://www.netlify.com/).

## 📱 UI & UX Design

L'interfaccia è stata ottimizzata specificamente per l'uso a una mano durante gli acquisti:
* Blocco dell'overscroll (niente effetto "rimbalzo" del browser).
* Input personalizzato per le unità di misura (Select "intelligente" con ricerca).
* Iconografia vettoriale inline (SVG) a zero-caricamento.
* Colori ad alto contrasto per la massima visibilità anche all'aperto.

---
*Progetto creato per ottimizzare il tempo, il carburante e la qualità della spesa.*
