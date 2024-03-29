# Säker kommunikation över internet


## Exempel på tentafrågor
### Redis

a) Hur skiljer sig Redis från andra databaser? Välj ett exempel att jämföra med, antingen SQL eller NoSQL.

b) Ge ett exempel på när man kan använda Redis och beskriv varför det är lämpligt i den här situationen.

### Headers

Beskriv och ge ett exempel på hur HTTP-headers kan förebygga attacker.

### Hash och Salt

a) Du har en hashingalgoritm som bara fungerar på strängar som är tal (exempelvis "15681291"). Algoritmen fungerar som så att den dubblerar talet och sedan subtraherar 2. Vad blir hashen av strängen "1000"?

b) Vad blir hashen om du i ovanstående exempel har saltet "10"?

c) Låt oss säga att du bara hashar (utan salt) dina lösenord och din databas läcker. Kan hackern få ut lösenorden i klartext? Resonera.

### Miljövariabler
 Vad är syftet med med miljövariabler? Hur kan de skydda dig i ett säkerhetsperspektiv?

 ### RBAC

 Vad menas med Principle of Least Privilege?

 Vad menas med Deny by Default?

 Vilka begränsningar har ett auktoriseringssystem som endast bygger på roller?

 ### TLS
 Förklara TLS-handshake.

 Vad är skillnaden på assymmetrisk och symmetrisk kryptering? Vad är för- och nackdelarna mellan de båda?

 ### OAuth 2.0
Förklara OAuth 2.0 handshake.

Varför skulle man vilja använda sig av OAuth 2.0? Finns det några nackdelar?

### XSS
Beskriv en hemsida. Beskriv sedan också en feature som skulle kunna vara sårbar för XSS. Förklara hur man kan förebygga en sådan attack.

### CSRF
Är CSRF alltid en sårbarhet om sidan är sårbar för XSS?

Förklara hur man skulle kunna bli utsatt för en XSS-attack.

### JWT
Förklara steg för steg hur man genererar en token med claims: {user: 'peter'}. Du behöver inte ha verkliga base64-värden.

