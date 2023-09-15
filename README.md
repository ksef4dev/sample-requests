# sample-requests

Przykładowe wywołania w formacie Jetbrains Http Client

https://www.jetbrains.com/help/idea/exploring-http-syntax.html

W cepu uruchomienia wywołań należy utworzyć plik: `http-client.private.env.json` (https://www.jetbrains.com/help/idea/exploring-http-syntax.html#environment-variables) i umieścić w nim:

- Aktualny token sesyjny jako `token`
- Do nawiązania sesji interaktywnej potrzebny jest także `encryptedToken`

````json
{
  "test": {
    "token": "............................",
    "encryptedToken": "................................"
  }
}
````

# UUruchomienie poza IntelliJ

https://www.jetbrains.com/help/idea/http-client-cli.html
