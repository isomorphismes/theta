# Fixed charcoal renderer-bakeoff chrome

Application windows use the shared theme at android-NDK
e8b67dfc67776c2b8da919785d15f38d68c91db0. Owned WebView content explicitly uses
#212121, #2F2F2F and #383838 surfaces, restrained #454545 borders and F4/B4 text.
The existing native/web renderers change only neutral clear colours; per-vertex
theta/Wegert data, mesh, camera, sampling and gesture authority remain unchanged.
The deck.gl adapter is unchanged; its canvas composition still requires actual
renderer-by-renderer visual qualification.

Only existing Kotlin colour expressions are changed. No Java/Kotlin source,
framework or application architecture is introduced. Existing renderer and
Idriç build boundaries remain in force.

The inherited Android debug build has no preserved keystore/expected signer.
Its outputs are fixtures, not approved installed-app upgrades. Both-mode
API29/API34 visual/lifecycle, full six-renderer parity and physical C67 checks
remain pending; a source build is not visual acceptance.
