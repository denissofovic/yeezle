# Yeezle Mobile App

Android aplikacija bazirana na web igrici [yeezle.xyz](https://www.yeezle.xyz/) — dnevnoj igri pogađanja u kojoj korisnik pokušava otkriti misterioznu pjesmu Kanyea Westa na osnovu ponuđenih tragova (album, broj pjesme, dužina, gostujući izvođači), po uzoru na Wordle format.

## O projektu

Aplikacija donosi koncept web igre Yeezle u nativno Android okruženje, uz standardni Wordle-stil gameplaya — korisnik ima ograničen broj pokušaja da pogodi pjesmu, a nakon svakog pokušaja dobija povratnu informaciju (tačan pogodak, blizu, netačno) na osnovu koje sužava izbor.

## Tehnologije

- **Platforma:** Android
- **Build sistem:** Gradle (Kotlin DSL)

## Pokretanje

```bash
git clone https://github.com/denissofovic/yeezle-mobile-app.git
cd yeezle-mobile-app
./gradlew build
```

Projekat se može otvoriti direktno u Android Studiju kao standardni Gradle projekat.

## Autor

Denis Sofović
