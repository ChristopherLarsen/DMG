# How to do a release

1. Create a new release for the new version, add the .dmg file in it.
2. Get the url and update the appcast.xml with the new download location.
3. Delete the appcast.xml from the 0.0.0 Release, with it's download link pointing at the new release version.
4. Drag the new appcast.xml into the 0.0.0 Release. It needs to always have a static url so Sparkle can find it.

