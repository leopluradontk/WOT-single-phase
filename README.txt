TK WALCOTT SINGLE-PHASE IPAD VIEWER - R06

GITHUB UPLOAD
1. Extract this ZIP on your computer.
2. Upload the contents to the root of your GitHub repository: index.html,
   sw.js, manifest.webmanifest, icon.png, the full folder, and optional CSV.
   Upload the full folder as a folder; do not flatten its numbered JSON files.
   Upload extracted files, not the ZIP. Each model file is below 5 MB.
3. Enable GitHub Pages for the branch and root folder, as with your last model.
4. Open the GitHub Pages website link in Safari on the iPad.
5. Leave it open online until Controls says Offline ready. It caches about
   50 MB, including detailed geometry. Then Share > Add to Home Screen.
6. Open the new Home Screen icon once online. Test airplane mode before relying
   on offline access. iPadOS can clear website storage when space is low.

FEATURES
Touch orbit / pinch zoom / two-finger pan; Walk and Fly with touch arrows;
WASD, adjustable speed, focus, pivot, home, previous view, top/front/side;
multi-select, hide, isolate, show all; source-name and assembly-path search;
ground-up installation slider, play/pause, stage assignments, exploded views;
detailed hologram, wireframe and multi-part explosion; light/dark, render quality,
image capture, TK logo, Home Screen installation and offline caching.

MEASURING
Controls > Start measurement. Parts return to the installed position, and
hidden parts are restored. Pick two points on visible parts. Rotate and zoom
between picks. Choose Surface point or Nearest triangle vertex. Original
unsimplified tessellation is loaded for the picked part, so measurements do
not use the simplified display surface. The dimension line stays in the model
as you rotate. Multiple measurements are supported; CSV exports all dimensions,
part names, distances, source coordinates and absolute source X/Y/Z offsets.
Source dimensions are millimetres. Viewer vertical is source Z. Surface picks
are approximate (1 mm tessellation setting), not certified CAD dimensions.
Changing installation/explosion clears dimensions. Reloading clears all edits.

SOURCE / LIMITS
24,957 drawable part occurrences; 1,373 distinct geometries. Source STEP has
one phase. No other phases were copied or invented. All drawable part names
and their assembly paths are retained, including generic names such as SOLID
and COMPOUND. Another 611 leaf records had no triangulatable surfaces.
Original scene: 40.4 million triangles; simplified scene: 3.2 million triangles.
Parts are batched for fewer draw calls while retaining individual selection.
The installation order is illustrative and editable, not an approved sequence.
Hologram explosion operates on selected parts; no internal subparts are invented.
Measurement and code/data checks were performed; browser/iPad rendering could
not be run in this build environment. Please check navigation on your iPad.

UPDATING
Keep the complete folder structure together. This package uses a new offline
cache version distinct from previous viewers. To return to the previous model,
keep a copy of its repository files before replacing them.
