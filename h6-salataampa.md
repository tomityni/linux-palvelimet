# h6 Salataampa
# x) Lue ja tiivistä. Tiivistelmäksi riittää muutama ranskalainen viiva per artikkeli. (Tässä alakohdassa ei tarvitse tehdä testejä tietokoneella)

## Let's Encrypt 2024: How It Works
Automaattisesti hallinnoi varmenteiden myöntämistä ja uusimista.
Käyttää ACME-protokollaa verkkotunnuksen omistajuuden vahvistamiseen ja varmenteiden asentamiseen.

## Lange 2024: Lego: Obtain a Certificate: Using an existing, running web server (vain tämä kappale, ei "Running a script afterward" tai myöhempiä)
Opastaa sertifikaatin hallintaa Lego nimisellä ohjelmalla.
Sertifikaatin käyttötapauksia on useampia, mutta kyseinen kappale keskittyy jo toiminnassa olevien verkkopalvelimien sertifiointiin

## The Apache Software Foundation 2025: Apache HTTP Server Version 2.4 [Official] Documentation: SSL/TLS Strong Encryption: How-To: Basic Configuration Example (Ei "Cipher Suites and Enforcing Strong Security" eteenpäin. Name based virtual host -tiedostossa tarvitset vain SSLEngine, SSLCertificateFile ja SSLCertificateKeyFile -asetukset)
Apache HTTP -palvelimen perus SSL/TLS -asetukset sisältävät SSL:n käytön (SSLEngine) ja varmenteen tiedoston (SSLCertificateFile) sekä yksityisavaimen tiedoston (SSLCertificateKeyFile) määrittämisen.
Nämä asetukset sisältyvät virtuaalipalvelimen kokoonpanoon turvallisten yhteyksien varmistamiseksi.

# a) Let's. Hanki ja asenna palvelimellesi ilmainen TLS-sertifikaatti Let's Encryptilta. Osoita, että se toimii. 


# b) A-rating. Testaa oma sivusi TLS jollain yleisellä laadunvarmistustyökalulla, esim. SSLLabs (Käytä vain tavanomaisia tarkistustyökaluja, ei tunkeutumistestausta eikä siihen liittyviä työkaluja)
