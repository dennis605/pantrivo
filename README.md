# Pantrivo Legal Site

Diese statische Mini-Site ist fuer App Store, Google Play und In-App-Verlinkung gedacht.
Sie braucht keine eigene "echte" Website und kann sehr leicht veroeffentlicht werden.

## Enthaltene Seiten
- `index.html`
- `privacy.html`
- `terms.html`
- `subscription-terms.html`
- `support.html`

## Einfache Deploy-Optionen

### GitHub Pages
1. Dateien in diesem Ordner in ein eigenes Repo oder in einen veroeffentlichten Branch legen.
2. GitHub Pages fuer diesen Ordner bzw. Branch aktivieren.
3. Die finalen URLs notieren, z. B.:
   - `https://<user>.github.io/<repo>/privacy.html`
   - `https://<user>.github.io/<repo>/terms.html`
   - `https://<user>.github.io/<repo>/subscription-terms.html`
   - `https://<user>.github.io/<repo>/support.html`

### Vercel
1. Repo in Vercel importieren.
2. Als Root Directory `legal-site` waehlen.
3. Das Projekt als statische Seite deployen.
4. Die finalen URLs in EAS bzw. `.env.local` eintragen.

## Danach in Pantrivo setzen
Setze die produktiven URLs in EAS oder lokal:

- `PRIVACY_POLICY_URL`
- `TERMS_OF_USE_URL`
- `SUBSCRIPTION_TERMS_URL`
- `SUPPORT_EMAIL`

## Vor dem Go-live pruefen
- Inhalte juristisch gegenpruefen
- Kontaktadresse vervollstaendigen
- Support-Mailbox testen
- URLs in `preview` und `production` verifizieren
