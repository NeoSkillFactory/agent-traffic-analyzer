# agent-traffic-analyzer

![Audit](https://img.shields.io/badge/audit%3A%20PASS-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![OpenClaw](https://img.shields.io/badge/OpenClaw-skill-orange)

> Analyzes and visualizes communication patterns between OpenClaw agents to identify bottlenecks and suggest optimization strategies.

## Features

- Extract and analyze message flow patterns between OpenClaw agents
- Generate visualizations of communication networks and traffic volumes
- Identify bottlenecks and inefficiencies in agent interactions
- Suggest optimization strategies for improved agent coordination
- Export analysis reports in multiple formats (JSON, CSV, DOT)
- Compare historical communication patterns over time

## Usage

```bash
# Analyze a communication log file
agent-traffic-analyzer analyze <logfile.json>

# Generate a network visualization
agent-traffic-analyzer visualize <logfile.json> --format dot

# Generate a full report
agent-traffic-analyzer report <logfile.json> --output report.json

# Show summary statistics
agent-traffic-analyzer summary <logfile.json>

# Find bottlenecks
agent-traffic-analyzer bottlenecks <logfile.json>
```

## Quick Start
## Installation

```bash
npm install
```

## GitHub

Source code: [github.com/NeoSkillFactory/agent-traffic-analyzer](https://github.com/NeoSkillFactory/agent-traffic-analyzer)

## License

MIT © NeoSkillFactory