# GOOD TROUBLE

A pocket-sized radio that refuses to be quiet about being watched.

> "Never be afraid to make some noise and get in good trouble, necessary trouble."
> — John Lewis

## What this is

A $5 ESP32 that broadcasts a short Bluetooth advertisement — a message you chose,
cycling through a list, in the open 2.4 GHz band that belongs to everyone. It is
a picket sign made of radio. You hold it up by turning it on.

Mass signal-collection works by treating your body's emissions as data you never
agreed to hand over. It logs the devices you carry, correlates who moves with
whom, and calls the pattern a "fingerprint." It does this to people who committed
no crime, on the theory that everyone is a suspect waiting to be matched. The
consent was never asked for. This is one small way to answer in the same medium:
not by hiding — that's a different tool for a different day — but by transmitting,
plainly and on purpose, that you know you're being read and you do not agree.

## The ethic

You bring your body and a sign and you put yourself out there. That's the whole
thing. A protest is people choosing to be **seen**, together, taking what comes.

So this device is loud, legible, and proud of it. It does not impersonate anyone.
It does not jam, flood, or reach into anyone else's equipment. It does not hide
who's holding it. It says its piece in your own words and lets itself be logged —
because being undeniable is the point, and because the line between protest and
sabotage is the line between your signal and someone else's receiver, and we stay
on our side of it. Not because the watchers earned the courtesy. Because that's
what makes it good trouble and not just trouble.

## What it is NOT — and must never become

- **Not a jammer or a flood.** Low power, ordinary interval, one beacon per body.
  Cranking power or duty to drown the band is a blockade, not a sit-in — it's
  illegal interference and it silences your own crowd first. The firmware is tuned
  to coexist. Keep it there.
- **Not a disguise for someone else's device.** The OUI is made-up and
  self-assigned. Never wear a real vendor's identity or clone a real network.
  Your sign is your own name, not a stolen one.
- **Not a way to touch their gear.** This emits *your* speech into a public commons.
  It does nothing to anyone's hardware. That restraint is the integrity of the act.
- **Not a cloak.** It does not hide you — it does the opposite, on purpose. A
  distinctive recurring beacon is easy to log and easy to fingerprint. On a day
  you need to be unread instead of counted, this is the wrong tool. Go silent
  another way.

## Files

- `good_trouble/good_trouble.ino` — the beacon. Cycles your messages; edit the
  `MESSAGES[]` array to say what you mean.
- `good_trouble_config/good_trouble_config.ino` — same beacon, but set your message
  from a phone via a one-time Wi-Fi form that shuts off after you save.
- `FLASH_GUIDE.md` — plain-language, no experience needed.

## Consent

A sit-in works because people consent to being seen doing it. Anyone who flashes
this is holding up a sign in the open and choosing to be counted. Make that choice
knowingly. That knowing is the dignity of it.

Bring your body. Bring your sign. Get in good trouble.
