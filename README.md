# Insult-o-matic 3000 💨

A very silly random insult generator, made by Craig & Niall.

> *"the majestic nose hair of a Norwegian lollipop lady"*

## The story

This started life as a spreadsheet project between a dad and his son — an Excel file
that bolted together random words with `CHOOSE` and `RANDBETWEEN` to produce insults
like *"the smelly feet of a Scottish pelican"*. It made us laugh so much we turned it
into a web app.

Every insult follows the time-honoured formula:

```
the [adjective] [body part] of a [descriptor] [creature]
```

With ~90-100 words per category, that's over **80 million** possible insults.

## Features

- 🎰 Slot-machine style word reveal
- 🔊 Sound effects generated entirely in code (raspberry, sad trombone, fanfare)
- 📤 Share button to send insults to your victims
- 🎉 Emoji confetti
- 📱 Mobile-first, works offline, no dependencies

## Adding your own words

All the words live in [`words.json`](words.json) — just add entries to any of the
four lists (`adjectives`, `bodyParts`, `descriptors`, `creatures`) and redeploy.

## Running it

It's a single static page. Host it anywhere (we use Cloudflare Pages), or run it
locally with any web server:

```
python3 -m http.server
```

then open http://localhost:8000

---

*No pelicans were harmed in the making of this app.*
