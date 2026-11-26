# Element Web for TOS 7

Element Web is a browser client for [Matrix](https://matrix.org/). This package serves the official Element Web 1.12.36 client on x86_64 and aarch64.

Open the app from App Center or visit `http://NAS:19160`. Put the same endpoint behind a trusted HTTPS reverse proxy before signing in, to provide the browser APIs used for encrypted communications and calls. The upstream default homeserver is `matrix.org`. To use another Matrix service, select **Edit** on the sign-in screen and enter its address.

The NAS serves the client files. Matrix accounts and room history live on the selected homeserver, while the browser keeps session state and encryption keys. Set up key backup in Element before clearing site data or moving to a new browser.

[Privacy policy](PRIVACY.md) · [Upstream documentation and license](https://github.com/element-hq/element-web)
