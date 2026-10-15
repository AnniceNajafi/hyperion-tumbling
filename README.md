# Hyperion, tumbling

Interactive viewer for a term project on the chaotic rotation of Saturn's moon Hyperion.

**Live app:** https://annicenajafi.github.io/hyperion-tumbling/

It runs the planar spin–orbit model and the full 3D rigid-body Euler equations (gravity-gradient torque, RK4) in the browser, renders Hyperion with the Cassini shape model (Thomas, Joseph & Ansty 2018, NASA PDS, doi:10.26033/ewy3-jy61), samples the simulated lightcurve on Klavetter's 1987 observing nights (Klavetter 1989, AJ 97, 570), and compares the result against 1,500-run ensembles from the project's analysis.

The page is a single self-contained `index.html`; the only external resources are three.js from jsDelivr and Google Fonts.
