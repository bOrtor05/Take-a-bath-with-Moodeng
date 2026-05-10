# Moodeng-s-Sauna

## Group Information

| | |
|---|---|
| Group name | |
| Member 1 | Jiraprapha Kwankla 67070504002 |
| Member 2 | Watcharaporn Pengsri 67070504011 |
| Member 3 | Sujira Chokjaraskij 6070504013 |
| Course | INC272: Web-Based IoT Applications (2026) |

* * *

## Project Goal

The project is a web-based temperature monitoring and heater control simulator for “Moodeng’s Sauna.”
 Its main goal is to demonstrate how an operator can:
- Monitor real-time temperature
- Control a heater remotely
- Set a desired target temperature
- Receive alerts when unsafe temperatures occur
- Observe system connection status

* * *

## Simulator Features Used

Check every feature your project actually uses. **At least 2 features are required.**

- [ ] LED — 4 channels, toggle on/off
- [ ] PSW — 4 push switches, read state
- [X] ADC — 4 analog channels, read sensor values
- [X] PWM — 4 channels, control duty ratio

* * *

## Interface Features

### Monitoring Elements

List each element that reads and displays data from the simulator.

| Element | What It Shows | Simulator Feature |
|---------|--------------|-------------------|
| e.g. Gauge | ADC channel 0 voltage level | ADC ch.0 |

### Control Elements

List each element that sends a command to the simulator.

| Element | What It Does | Command Sent |
|---------|-------------|--------------|
| e.g. Toggle button | Turn LED 0 on or off | `led,0,2` |

* * *

## How to Run

1. Start the mock hardware server:
   ```bash
   cd simulator/mock-hardware-server
   npm start
   ```
2. Open `index.html` using VS Code Live Server.
3. Check the browser console — a WebSocket connection message should appear.
4. Check the server terminal — `[CONNECT]` should be printed.

* * *

## File Structure

List the main files in your project and briefly describe each one.

```
project-folder/
├── index.html      — main page
├── main.js         — application logic
└── ...
```

* * *

## Known Limitations

List anything that does not work as intended, or features you planned but did not complete.
If everything works, write "None".

* * *

## Screenshots

Add one or two screenshots of the running application.
In Markdown, use: `![description](path/to/image.png)`
