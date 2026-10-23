# another-webflasher-for-m5tab5

A web flasher for the M5Stack Tab5's ESP32-P4, over its USB-C port.

**Open it: <https://sudrien.github.io/another-webflasher-for-m5tab5/>**

For now the page only checks that the browser can ask for permission to
the Tab5's serial port: Chrome, Edge, and Firefox 151 or later on
desktop. Safari has no Web Serial.

MIT License; see [LICENSE](LICENSE).

## Dependency report

Every Monday, `.github/workflows/deps.yml` runs `tools/depcheck.py` on
each Tab5 project's `dependencies.lock` -- against the Espressif
registry, the projects' git remotes and ESP-IDF's tags -- and keeps one
open issue here, "Dependency updates", saying what is newer. It changes
nothing in the projects. Locally, from a project's directory:

    python3 tools/depcheck.py .
