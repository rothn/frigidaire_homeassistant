# frigidaire_homeassistant
Cobbled together code from the Internet to make Frigidaire AC work with the latest HomeAssistant

Sources:
- https://github.com/bm1549/core/tree/frigidaire
- https://community.home-assistant.io/t/frigidaire-air-conditioners/198791/59

Key Changes:
- Added a version to the plugin manifest
- Updated the frigidaire plugin to support REST API changes
- Updated config\_flow.py to support homeassistant API changes

## Installation

Copy or clone this repository into a subdirectory of "config/custom\_components",
where "config" is the directory containing "homeassistant.yaml".

For example, executing `git clone` inside the "custom\_components" directory
will place this in "config/custom\_components/frigidaire\_homeassistant".

Then, restart HomeAssistant, add a Frigidaire device, and login using your
Frigidaire account.
