# characters

[![Go Reference](https://pkg.go.dev/badge/github.com/Mobilpadde/characters/v2.svg)](https://pkg.go.dev/github.com/Mobilpadde/characters/v2)

Just a few character helpers for Go

## Why

I've been in the situation where I had a need for all letters in the latin alphabet,
and always seem to google for the alphabet to make sure I remember all letters,
so I decided to make a simple package for this - and more, sorry!

I had a specific need for this again in [moths](https://github.com/Mobilpadde/moths),
and had it with searching to be sure 🤷

## docs

This contains two packages, one with [letters](letters/letters.go) and one with [numbers](numbers/numbers.go) (encoded as strings).

### letters

This is just an easier way to get the (current) english alphabet as either:

- [Lowercase](letters/letters.go#L5)
- [Uppercase](letters/letters.go#L8)
- [Combined](letters/letters.go#L5)

### numbers

Simply added as I didn't think want to create a repo for just letters 😶‍🌫️

This will provide numbers in different manners (as strings):

- [All](numbers/numbers.go#L5)
- [Even](numbers/numbers.go#L8)
- [Odd](numbers/numbers.go#L11)
- [Zero](numbers/numbers.go#L14)

---

kthnxbai
