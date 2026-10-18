# nova-trailer-relay

One static page that lets the Nova TV app (a Stremio client for Samsung TVs) play YouTube trailer
previews. YouTube refuses embeds from apps that run from local files (Error 153: no referrer);
the app embeds this page instead, which embeds YouTube from a real web origin and relays the
player's postMessage events.

Served by GitHub Pages: `https://droopram.github.io/nova-trailer-relay/?v=<youtubeId>&start=4&mute=0`
