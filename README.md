# sample-requests

Przykładowe wywołania w formacie Jetbrains Http Client

https://www.jetbrains.com/help/idea/exploring-http-syntax.html

W celu uruchomienia przykładowych wywołań należy utworzyć plik: `http-client.private.env.json` (https://www.jetbrains.com/help/idea/exploring-http-syntax.html#environment-variables) i umieścić w nim:

- aktualny token sesyjny jako `token`
- numer NIP jako `nip`
- do testowania nawiązania sesji interaktywnej potrzebny jest także `encryptedToken` i `challenge`. Można użyć klasy Java `EncryptAuthorizationToken` z repozytorium [ksef-java-sample](https://github.com/ksef4dev/ksef-java-sample), która po podaniu NIP i tokena autoryzacyjnego wyświetli zaszyfrowany token i challenge.

````json
{
  "test": {
    "token": "............................",
    "nip": ".........",
    "encryptedToken": "................................",
    "challenge": "...."
  }
}
````

# Uruchomienie poza IntelliJ

https://www.jetbrains.com/help/idea/http-client-cli.html
