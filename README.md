# American Epochs

An interactive instrument for navigating American history through a legitimacy-cycle framework — seven named epochs from 1941 to the present, rendered as an explorable timeline.

## The Epochs

| Epoch | Years | Theme |
|---|---|---|
| The American Ascendancy | 1941–1952 | Rise of hegemony; the structural pivot before victory |
| The Affluent Society | 1953–1965 | Postwar consensus at its apex; Keynesianism working |
| The Unravelling | 1966–1979 | Civil rights fracture, stagflation, Watergate, malaise |
| Morning in America | 1980–1991 | Reagan ideological regime change; Cold War vindication |
| The End of History | 1992–2007 | Liberal democratic consensus; the Fukuyama era |
| The Interregnum | 2008–2015 | Legitimacy collapse without a successor order |
| The Reckoning | 2016–Present | Accumulated debts arriving; no settled new order |

## Framework

The epochs trace two legitimacy cycles, each following a **Rise → Apex → Crisis** arc:

- **Cycle One: The New Deal Order (1941–1979)** — Ascendancy → Affluent Society → Unravelling
- **Cycle Two: The Reagan-Clinton Synthesis (1980–Present)** — Morning in America → End of History → Interregnum & Reckoning

Each cycle is ratified when the opposition party adopts its framework (Eisenhower accepting the New Deal; Clinton accepting Reaganism) and ends when its legitimacy conditions fail.

## The Instrument

`src/american-epochs.html` is a self-contained, zero-dependency interactive visualization:

- **Timeline bands** — colored epoch regions scaled by duration
- **Event layer** — key historical events plotted by year with toggle filters
- **President layer** — administration bars with party color
- **Statistical overlays** — crime rate, unemployment, S&P 500 (toggleable)
- **Detail panel** — click any epoch or event to read its interpretive annotation
- **Register system** — events tagged as *factual*, *structural*, or *argued* (the last rendered with a hatched pattern to flag interpretive claims)

## Usage

Open `src/american-epochs.html` directly in a browser — no build step, no server required.

## Source

`src/american-epochs_v1.md` contains the original written framework: full epoch justifications, structural logic, and theoretical grounding.
