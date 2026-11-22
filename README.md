# Trading Thermodynamics

An interactive three.js model of a trading floor, built from the physical setup described in the
*Signals & Threads* episode ["The Thermodynamics of Trading"](https://signalsandthreads.com/the-thermodynamics-of-trading/):
the raised floor and underfloor air plenum, rotatable floor diffusers, under-desk PC enclosures,
wheeled desks, power whips and modules, end-of-row network switches, and the air handlers that feed it all.

Click any label or object to see what the podcast actually said about it, and what was assumed.

## Running it

It's a single static page. three.js loads from a CDN, so there is no build step.

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765.
