# Foo

Madaling i-restart ang iyong aplikasyon mula sa simula at tanggalin ang nakaraang mga states.

## Paggamit

I-wrap ang iyong App widget sa `Foo` widget.

```dart
void main() {
  runApp(
    Foo(
      app: App(),
    ),
  );
}
```

Tawagin lamang ang `restart` static method kung gusto mong i-restart ang iyong application (ire-rebuild nito ang kalahatan na widget tree na para bang bago ang iyong app).

```dart
Foo.restart(context);
```

**Disclaimer :**
<br><br>Ire-restart lamang ng Foo ang sa application level ang iyong application.
<br><br>Ang Foo ay hindi ire-restart ang iyong application process sa OS Level.

## Mga mamaaring paggamitan ng Foo

Ito ang mga maaring paggamitan ng Foo (Hindi ito kumpleto):

- ang pag restart matapos ang logout
- ang pag restart matapos ang bigong pag initialize ng process
- ang pag restart matapos mangyari ang isang event sa app
- ...

## Pag Install

### Dependency
I-add lamang ang package as a dependency sa iyong pubspec.yaml file.
```yaml
dependencies:
    Foo: "^0.0.1"
```

## Pag Import
I-import ang package sa iyong code file.
```dart
import 'package:Foo/Foo.dart';
```

## License

Ang Foo ay inereleased under [MIT License](LICENSE)

## About Me

Ako ay hamak na isang Developer na kanigigiliwan ang pag-develop ng mga tools sa Flutter.

- Facebook [John Mar Lorenzo](https://www.facebook.com/lorenzojohnmar565)
- Instagram [@lrnzojanmar](https://www.instagram.com/lrnzojanmar/)