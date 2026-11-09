# Download & run locally

Eleven tools, apps, and research verifiers by Rishit Pradhan. The downloads below are public and do not require a GitHub account. Click a ZIP link, extract it, then follow its short guide.

**Start with Sift or Trellis for an API; QuietGrid, ThermoQueue, or Offcut Commons for a complete Python app.**

## Before you start

- **Python apps, browser demos, and research:** install [Python 3.10+](https://www.python.org/downloads/). On Windows, use `py -3` wherever a guide says `python3`.
- **Sift / Trellis APIs:** install [Node.js 22+](https://nodejs.org/en/download). No npm packages are required in the API downloads.
- Extract **all files**, open a terminal in the extracted inner folder, then run the listed command. Keep the terminal open while a server runs; Ctrl+C stops it.
- Both APIs use port 8787; the four browser demos use 8000. Run one at a time or choose another port using the project guide.

## Downloadable APIs

### Sift

CSV quality audits and streaming profiling.

**[Download ZIP](https://github.com/rishitpradhan-gif/sift/releases/download/v0.1.0/sift-api.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/sift/blob/main/engine/README.md) · [Source](https://github.com/rishitpradhan-gif/sift)

```sh
node server.mjs
```

Then open **http://127.0.0.1:8787/health** (JSON health check; this is an API server).

POST JSON to `/v1/profile`. Example request body:

```json
{"csv":"id,value\n1,10\n2,\n"}
```

OpenAPI JSON, a Dockerfile, examples, and tests are included.

### Trellis

Dependency planning, critical paths, and delay impact.

**[Download ZIP](https://github.com/rishitpradhan-gif/trellis/releases/download/v0.1.0/trellis-api.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/trellis/blob/main/engine/README.md) · [Source](https://github.com/rishitpradhan-gif/trellis)

```sh
node server.mjs
```

Then open **http://127.0.0.1:8787/health** (JSON health check; this is an API server).

POST JSON to `/v1/plan`. Example request body:

```json
{"tasks":[{"id":"A","duration":3,"dependsOn":[]}]}
```

OpenAPI JSON, a Dockerfile, examples, and tests are included.

## Complete local tools

### QuietGrid

Noise-aware routing on an editable synthetic floor map.

**[Download ZIP](https://github.com/rishitpradhan-gif/quietgrid/releases/download/local-v1/quietgrid-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/quietgrid/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/quietgrid)

```sh
python3 server.py
```

Then open **http://127.0.0.1:4311** in your browser.

### ThermoQueue

Compute scheduling with a modeled useful-heat credit.

**[Download ZIP](https://github.com/rishitpradhan-gif/thermoqueue/releases/download/local-v1/thermoqueue-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/thermoqueue/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/thermoqueue)

```sh
python3 server.py
```

Then open **http://127.0.0.1:4312** in your browser.

### Offcut Commons

Cutting-stock planning combined with supplier pickup routing.

**[Download ZIP](https://github.com/rishitpradhan-gif/offcut-commons/releases/download/local-v1/offcut-commons-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/offcut-commons/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/offcut-commons)

```sh
python3 server.py
```

Then open **http://127.0.0.1:4313** in your browser.

## Prebuilt browser apps

### Morphogenesis

Paint seeds and grow reaction–diffusion patterns.

**[Download ZIP](https://github.com/rishitpradhan-gif/morphogenesis-lab/releases/download/local-v1/morphogenesis-lab-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/morphogenesis-lab/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/morphogenesis-lab)

```sh
python3 serve.py
```

Then open **http://127.0.0.1:8000** in your browser.

### Rally Court

A playable tennis-inspired arcade game.

**[Download ZIP](https://github.com/rishitpradhan-gif/rally-court/releases/download/local-v1/rally-court-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/rally-court/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/rally-court)

```sh
python3 serve.py
```

Then open **http://127.0.0.1:8000** in your browser.

### World Garden

Build and explore a local isometric island.

**[Download ZIP](https://github.com/rishitpradhan-gif/world-garden/releases/download/local-v1/world-garden-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/world-garden/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/world-garden)

```sh
python3 serve.py
```

Then open **http://127.0.0.1:8000** in your browser.

### Wearable Signals

Explore an interface driven by simulated wearable signals.

**[Download ZIP](https://github.com/rishitpradhan-gif/wearable-signal-lab/releases/download/local-v1/wearable-signal-lab-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/wearable-signal-lab/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/wearable-signal-lab)

```sh
python3 serve.py
```

Then open **http://127.0.0.1:8000** in your browser.

## Research verifiers

### Fourteen

Reproduce the sharp fourteen-ply fixed-pairing obstruction.

**[Download ZIP](https://github.com/rishitpradhan-gif/fourteen/releases/download/local-v1/fourteen-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/fourteen/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/fourteen)

```sh
python3 verify.py
python3 attack.py
```

Results appear in the terminal; no local website is started.

### Prerequisite Pairings

Check paired-reply legality and quotient theorems.

**[Download ZIP](https://github.com/rishitpradhan-gif/prerequisite-pairings/releases/download/local-v1/prerequisite-pairings-local.zip)** · [Simple guide](https://github.com/rishitpradhan-gif/prerequisite-pairings/blob/main/LOCAL.md) · [Source](https://github.com/rishitpradhan-gif/prerequisite-pairings)

```sh
python3 verify.py
```

Results appear in the terminal; no local website is started.

## Troubleshooting

- **Nothing opens automatically:** copy the local URL above into your browser. For APIs, `/health` returns JSON; there is no website UI in the API-only bundle.
- **Missing file:** you are probably outside the extracted inner folder. Open that folder and try again.
- **Port busy:** browser and Python app launchers accept `--port 8001`. APIs accept the `PORT` environment variable; see their included README.
- **No terminal experience?** On Windows, open the extracted folder, click the address bar, type `powershell`, and press Enter. On macOS, open Terminal, type `cd `, drag the extracted inner folder into the window, and press Enter.
- **Running on someone else's computer:** download and extract again there; keep the entire folder together, not only its launcher.

## What the downloads contain

Browser bundles contain prebuilt app files and a small loopback-only Python web server. Python tools include their engines, examples, and web UI. API bundles contain dependency-free Node.js source and OpenAPI contracts. Research bundles contain proofs and executable checks.

The Wearable Signals demo uses fabricated signals; World Garden uses local simulated companions. QuietGrid, ThermoQueue, and Offcut Commons are bounded planning prototypes. Read each project's README for its actual assumptions. Hosted Sites access settings do not restrict these public local downloads.

[Machine-readable download catalog](tools.json) · [Local package checks](docs/local-download-verification.json)
