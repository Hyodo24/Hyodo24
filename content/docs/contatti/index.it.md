---
title: "Contatti"
---
<html lang="it">
<head>
    <style>
        /* Stili Generali del Corpo */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            color: #333; /* Colore testo principale */
            line-height: 1.6;
        }
        /* Stile del Contenitore Principale */
        .container {
            max-width: 800px;
            margin: 20px auto; /* Centra il contenitore nella pagina */
            padding: 30px;
            border-radius: 8px; /* Angoli arrotondati */
        }
        /* Stili per Intestazioni */
        h1, h2, h3 {
            color: #444; /* Colore scuro per le intestazioni */
            margin-bottom: 15px;
        }
        h1 {
            text-align: center;
            color: #b04e2a; /* Un colore più vibrante per il titolo principale (simil-tema blowfish) */
        }
        h2 {
            border-bottom: 2px solid #eee; /* Linea sotto le sottosezioni */
            padding-bottom: 5px;
            margin-top: 30px; /* Spazio sopra le sottosezioni */
        }
        /* Stili per Paragrafi e Liste */
        p {
            margin-bottom: 10px;
        }
        ul {
            list-style: none; /* Rimuove i bullet point standard */
            padding: 0;
            margin-bottom: 20px;
        }
        ul li {
            margin-bottom: 5px;
            padding-left: 15px;
            position: relative;
        }
        ul li::before {
            content: '•'; /* Aggiunge un bullet point personalizzato */
            color: #b04e2a; /* Colore del bullet point */
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
        /* Stile per la Mappa Incorporata */
        .map-container {
            overflow: hidden;
            padding-bottom: 56.25%; /* Rapporto aspetto 16:9 */
            position: relative;
            height: 0;
            margin-bottom: 20px;
            border: 1px solid #ddd; /* Bordo per la mappa */
            border-radius: 4px;
        }
        .map-container iframe {
            left: 0;
            top: 0;
            height: 100%;
            width: 100%;
            position: absolute;
            border: 0; /* Rimuove il bordo predefinito dell'iframe */
        }
        /* Stili per il Modulo di Contatto */
        .contact-form label {
            display: block; /* Ogni etichetta su una nuova riga */
            margin-bottom: 5px;
            font-weight: bold;
        }
        .contact-form input[type="text"],
        .contact-form input[type="email"],
        .contact-form textarea {
            width: calc(100% - 22px); /* Larghezza completa meno padding e bordo */
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc; /* Bordo sottile */
            border-radius: 4px;
            box-sizing: border-box; /* Include padding e border nella larghezza totale */
        }
        .contact-form textarea {
            resize: vertical; /* Permette il ridimensionamento verticale */
            min-height: 100px;
        }
        .contact-form button {
            background-color: #b04e2a; /* Colore del pulsante */
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer; /* Cambia cursore al passaggio */
            font-size: 16px;
            transition: background-color 0.3s ease; /* Effetto al passaggio del mouse */
        }
        .contact-form button:hover {
            background-color: #8c3b20; /* Colore più scuro al passaggio */
        }
        /* Stile del Footer */
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eee;
            color: #777;
            font-size: 0.9em;
        }
        /* Responsiveness Base */
        @media (max-width: 600px) {
            .container {
                margin: 10px;
                padding: 15px;
            }
            .contact-form input[type="text"],
            .contact-form input[type="email"],
            .contact-form textarea {
                width: calc(100% - 20px); /* Regola per schermi più piccoli */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Indirizzo</h2>
        <p>Via Nazionale Olivarella 142</p>
        <p>98044 Milazzo (ME), Sicilia</p>
        <h2>Orari di Apertura</h2>
        <ul>
            <li>Lunedì - Giovedì: 09:00 - 22:00</li>
            <li>Venerdì - Sabato: 09:00 - 00:00</li>
            <li>Domenica: 10:00 - 21:00</li>
            <li>*Gli orari potrebbero variare durante le festività. Contattateci per maggiori informazioni.*</li>
        </ul>
        <h2>Dove Trovarci</h2>
        <div class="map-container">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2105.749023849552!2d15.26780769396347!3d38.21045958619623!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1314644a47d2d31d%3A0xf69c0d9c490d1f7c!2sVia%20Olivarella%20Nazionale%2C%20140%2F142%2C%2098044%20Olivarella-Corriolo%20ME!5e0!3m2!1sit!2sit!4v1717667822452!5m2!1sit!2sit"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        </div>
        <p style="text-align: center;">Siamo nel cuore di Olivarella. Clicca sulla mappa per le indicazioni stradali!</p>
        <h2>Inviaci un Messaggio</h2>
        <p>Hai domande, suggerimenti o vuoi prenotare? Compila il modulo qui sotto e ti risponderemo al più presto!</p>
        <form class="contact-form" action="#" method="POST">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="subject">Oggetto:</label>
            <input type="text" id="subject" name="subject">
            <label for="message">Messaggio:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Invia Messaggio</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2025 Zanzibar Bar. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>