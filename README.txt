COASTAL GARDENS — MOBILE PROTOTYPE + ORIGINAL 3D MODEL VIEWER

This package contains:
- index.html: playable 2D touchscreen city-life prototype (newly recreated, not original Unity gameplay)
- models.html: interactive 3D preview of 18 actual GLB assets recovered from the uploaded Unity Windows game data
- viewer.js: local WebGL renderer; no CDN or third-party runtime dependencies
- models/: 18 original LOD1 game models (bank, agency, police, shopping mall, cafe, flats, dealership, restaurants, houses, clinic, airport, bus, train and airplane)
- manifest.webmanifest and sw.js: Progressive Web App support

HOW TO USE
1. Unzip the package.
2. Upload ALL contents to an HTTPS static host, maintaining the folder structure. (For testing on a computer, use a local web server rather than file:// for the model gallery.)
3. On your iPhone, open the hosted URL in Safari and select Share > Add to Home Screen.
4. The 2D game is playable using the left joystick and INTERACT button. Tap 3D CITY MODELS to examine the recovered GLB assets.
5. Open individual models at least once online to cache them for later offline access; their offline availability depends on Safari maintaining the site's storage.

LIMITATIONS
This is not a native .ipa app and is NOT a fully reconstructed original Unity 3D game. The model viewer displays recoverable game meshes and approximate base-colour shading, not full Unity materials, scripts, or interiors. It has not been tested on an actual iPhone. Native iOS builds require Unity project reconstruction, iOS build support, a Mac/Xcode, and Apple signing. A ZIP by itself is not an installable iPhone app.
