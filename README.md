# MMERGENT
An impossible specimen: an experimental, touch-reactive six-sided organism.

## Play
Open [MMERGENT](https://udeudeude.github.io/Mmergent/) on a phone or desktop after enabling GitHub Pages (Deploy from branch: main, root).

Drag to rotate; tap a visible face or press **Mutate** to alter its structures. Pinch to scale. **Tilt** requests motion access on supported phones. **Camera** overlays the specimen on a live camera view (permission required). **Sound** enables synthesized mutation tones. **Reset** restores the original specimen. Desktop: arrow keys rotate, space mutates.

## Scope and next frontier
This first version is an original procedural cube toy. It **does not yet track the physical Merge Cube**. The camera is a backdrop, not marker recognition. Actual six-face tracking and stable camera-space registration require a dedicated computer-vision implementation and physical testing with a Merge Cube.

No external dependencies, accounts, image assets, or build steps. The app runs from a single HTML file. Camera and motion permissions require a secure origin such as GitHub Pages.

## Privacy
Camera frames are displayed locally and are not uploaded. Audio is synthesized locally.
