# Launchpad

Upcoming rocket launches on your TRMNL: mission, rocket, launch pad, destination and a T-minus countdown.

<a href="https://trmnl.com/recipes/189917"><img width="150" alt="Works with TRMNL" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" /></a>

## Settings
- **Amount of launches:** pick 1 (always the next launch) up to 10 upcoming launches to rotate randomly

Data from [The Space Devs](https://thespacedevs.com/) Launch Library, cached on my end and refreshed every 15 minutes to respect their rate limits. Times are in UTC.

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Questions or ideas? trmnl@achtnegen.nl or @Bastronautica on Discord.
