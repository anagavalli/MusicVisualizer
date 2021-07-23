# Dream Visualizer

Run "python -m SimpleHTTPServer" to view the visualizer in your browser at localhost:[portnum].

Camera controls are listed on the page under the canvas (press 'p' to play song, click screen to fullscreen and enable camera controls, esc to leave)

Used k3d (http://k3d.ivank.net) to parse OBJ files, referenced this pointer lock demo (https://mdn.github.io/dom-examples/pointer-lock/)

All planet textures are from http://planetpixelemporium.com/planets.html

Choosing custom songs from local file system only works on Firefox due to CURS restrictions

If you're wondering, the 'Planetary anti-explosion measures' controls the spawn rate of particles (high slider value = less particles)

index.html is the main page, javascript files are in js/* with libraries in js/lib