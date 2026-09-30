# briefing-refresh

One static page. A link opens it with an address and a key after the `#`; the page calls that
address once, closes its own tab on success, and stays open with the reason on failure.

It exists because a Google Apps Script page cannot close its own tab. It holds no addresses,
keys or data of its own.
