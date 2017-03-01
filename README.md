For the functions installing addons, you need to create a folder "extensions" from where you run the django project and place there the XPIs.
The Extension needs to have the name of its install.rdf file.

Currently they are:

- [CanvasBlocker@kkapsner.de.xpi](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/)
- [jid1-zUrvDCat3xoDSQ@jetpack.xpi](https://addons.mozilla.org/de/firefox/addon/google-no-tracking-url/)
- [https-everywhere@eff.org.xpi](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)
- [uBlock0@raymondhill.net.xpi](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
- [uMatrix@raymondhill.net.xpi](https://addons.mozilla.org/en-US/firefox/addon/umatrix/)
- [xclear@as-computer.de.xpi](https://addons.mozilla.org/en-US/firefox/addon/xclear/)
- [{455D905A-D37C-4643-A9E2-F6FEFAA0424A}.xpi](https://addons.mozilla.org/en-US/firefox/addon/refcontrol/)
- [jid1-MnnxcxisBPnSXQ@jetpack.xpi](https://addons.cdn.mozilla.net/user-media/addons/506646/privacy_badger-2017.1.26.1-an+fx.xpi)

Things, that will not be included:

- Some cool addons. The addons list should be short and mostly privacy addons and important tweaks like classic theme restorer. Smaller addons like xclear are okay, but not too much.
- Your favourite performance setting. It's not the scope of the project to enable http pipelining because some site may load faster.

You're welcome to fork the project to create profiles with such features enabled.
Later some plugin system may be added. Then additional settings / addons could just be added via a config file.

