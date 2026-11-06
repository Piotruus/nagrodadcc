# Nagroda

Plugin `/nagroda` (Paper 1.21) - nagrody za Discord, TikTok i YouTube.

## Budowanie
Po pushu na GitHub zakładka **Actions -> Build -> Artifacts** zawiera gotowy plik `.jar`
(lub lokalnie: `mvn package`).

## Konfiguracja bota Discord
1. https://discord.com/developers/applications -> Bot -> włącz **Message Content Intent**.
2. Zaproś bota na serwer z uprawnieniami: View Channel, Send Messages, Read Message History.
3. Token wpisz do `plugins/Nagroda/config.yml` (`discord.token`) **na serwerze** albo ustaw
   zmienną środowiskową `NAGRODA_DISCORD_TOKEN`. Nigdy nie commituj tokena do repozytorium.

## Komendy
- `/nagroda` - menu nagród
- `/nagroda admin link|reset <nick> <discord|tiktok|youtube>`
- `/nagroda admin reload`
