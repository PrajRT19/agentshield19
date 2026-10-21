# AgentShield Dashboard

An **AI Security Platform** for monitoring, testing, and improving the security posture of your applications. It is designed for developers and security teams who need an integrated dashboard to visualize vulnerabilities and simulate attacks.

## Badges

## Table of Contents

- [Features](#features)
- [Demo / Screenshots](#demo--screenshots)
- [Requirements / Prerequisites](#requirements--prerequisites)
- [Installation](#installation)
- [Configuration / Environment variables](#configuration--environment-variables)
- [Usage / Examples](#usage--examples)
- [API / CLI reference](#api--cli-reference)
- [Project structure](#project-structure)
- [Roadmap / Known limitations](#roadmap--known-limitations)
- [Contributing](#contributing)
- [Tests](#tests)
- [License](#license)
- [Acknowledgements / Credits](#acknowledgements--credits)

## Features

- Monitor your security score in real time.
- Filter and expand vulnerability rows by severity.
- Start watch mode to track changes continuously.
- Inject attacks via the Attack Simulator.
- Apply fixes and trigger rescan to update your security score.
- Download vulnerability reports in JSON and HTML formats.
- Access help directly from the terminal.

## Demo / Screenshots

## Requirements / Prerequisites

## Installation

```bash
cd agentshield-dashboard
npm install
```

## Configuration / Environment variables

| Variable | Default | Description |
|----------|---------|-------------|
| — | — | See `BACKEND_INTEGRATION.md` for connecting to the AgentShield CLI. |

## Usage / Examples

Follow the Hackathon Demo Flow:

1. Navigate to the Dashboard and view the score of `28/100`.
2. Go to Vulnerabilities, filter by critical, and expand rows.
3. Start Watch Mode.
4. Open the Attack Simulator and inject attacks.
5. Apply a Fix, then trigger a Rescan; the score jumps to `82/100`.
6. Go to Reports and download JSON/HTML.
7. Open the Terminal and type `help`.

## API / CLI reference

## Project structure

## Roadmap / Known limitations

## Contributing

## Tests

## License

## Acknowledgements / Credits
---