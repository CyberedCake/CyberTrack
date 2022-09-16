<p align="center">
	<img width="120" height="120" src="assets/images/logo.svg">
</p>

# CyberedTrack
Track's Cybered's favorite Minecraft servers. [Find the original here](https://github.com/Cryptkeeper/Minetrack) and [check out the original website](https://minetrack.me).

## Installation
1. Node 12.4.0+ is required (you can check your version using `node -v`)
2. Make sure everything is correct in ```config.json```.
3. Add/remove servers by editing the ```servers.json``` file
4. Run ```npm install```
5. Run ```npm run build``` (this bundles `assets/` into `dist/`)
6. Run ```node main.js``` to boot the system (may need sudo!)

(There's also ```install.sh``` and ```start.sh```, but they may not work for your OS.)

Database logging is disabled by default. You can enable it in ```config.json``` by setting ```logToDatabase``` to true.
This requires sqlite3 drivers to be installed.
