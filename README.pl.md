# Luna Demo

Galeria deweloperska libLuny — 77 widgetów z podglądami, interakcją i przykładami kodu.

> **Języki:** [Polski](README.pl.md) · [English](README.en.md) · [Deutsch](README.de.md)

## Część projektu Luna

Repozytorium jest częścią organizacji [LunaDesktop](https://github.com/LunaDesktop) i projektu **Luna** — pulpitu pisanego w Rust, bez GTK, Qt i GObject.

## Budowanie

```bash
git clone https://github.com/LunaDesktop/luna-demo.git
cd luna-demo
cargo build --release
```

Wymagania: Linux, Rust 1.80+, Wayland (dla aplikacji okienkowych).

## Uruchomienie

```bash
cargo run --release
```

## Dokumentacja

- Strona projektu: <https://luna.paganlinux.eu/>
- Dokumentacja deweloperska: <https://luna.paganlinux.eu/docs/>
- Wersja angielska: <https://luna.paganlinux.eu/en/docs/>
- Indeks API: <https://luna.paganlinux.eu/en/docs/api.html>

## Licencja

Kod jest dostępny na licencji **GPL-3.0-or-later**. Pełny tekst znajduje się w pliku [LICENSE](LICENSE).
