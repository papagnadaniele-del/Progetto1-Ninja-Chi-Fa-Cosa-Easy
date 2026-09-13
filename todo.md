# Turno Settimanale - Separazione Sale Operatorie / Servizi (v9)

## Modifiche richieste
- [x] Rimuovere da index.html (Sale Operatorie) le righe: Ancona, Accessi Vascolari, Sterilizzazione, Ufficio (mattina e pomeriggio)
- [x] Creare la vista "Turno Settimanale Infermieri - Servizi" con le righe rimosse
- [x] Aggiungere un selettore/tab in alto per passare tra "Sale Operatorie" e "Servizi"
- [x] I dati delle settimane per le righe spostate vanno nel nuovo turno Servizi
- [x] Mantenere Reperibilità e Assenze nel turno Sale Operatorie (sono a piena giornata, riguardano tutto)
- [x] Verificare anteprima visiva e stampa A4
- [x] Consegna finale

## Fix compatibilità wkhtmltopdf (QtWebKit)
- [x] Rimuovere NodeList.forEach() non supportato — sostituito con helper each()
- [x] Rimuovere URLSearchParams non supportato — sostituito con parsing manuale
- [x] Rimuovere Element.replaceWith() non supportato — sostituito con replaceChild()
- [x] Rimuovere classList.toggle() con 2 arg non supportato — sostituito con add/remove
- [x] Verificato PDF generato correttamente per entrambe le viste (Sale Operatorie + Servizi)
- [x] Verificato switch viste nel browser (Chromium)
- [x] Ridistribuito in produzione
