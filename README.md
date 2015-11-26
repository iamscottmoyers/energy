# energy

## Energy Provider Visualisation

For easy comparison of many energy provider rates with controls
for Gas / Electricity usage estimate and the duration you're
planning on keeping the tariff for.

Note that the rates are hardcoded in a CSV file so they're
probably not up to date and may contain mistakes. Also it
needs support for annual discounts (e.g. OVO discounts 60
pounds over the course of the year on their tariffs if you
only use the internet and their phone app for support
rather than email + phone, and that makes a big difference
that isn't recorded in this visualisation).

## Getting Started

```
git clone https://github.com/iamscottmoyers/energy.git
cd energy
python -m SimpleHTTPServer 8000 &
```

Then navigate to localhost:8000.
