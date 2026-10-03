# Survival++ Minecraft 26.2 charger port

This local port starts from Direwolf20-MC/ChargingGadgets `26.1` at `9e464f1c5fcdb5f02cb8b1020f0fa9c2f5b0e97a` (1.16.1). The upstream MIT license and attribution remain intact. It targets Minecraft 26.2, NeoForge 26.2.0.75, and Java 25.

The port updates the build to ModDevGradle 2.0.144 and migrates tag generation to registry keys. Upstream behavior remains: a crafted station consumes furnace fuel and charges one FE item. Its combined Survival++ dedicated-server load reached `Done` and shut down cleanly before the final Building Gadgets survival-policy edits. User-led charging and client checks are pending.

Build with `../custom-survival-starter/gradlew --offline --no-daemon --max-workers=1 -Dorg.gradle.jvmargs=-Xmx1536m jar`.
