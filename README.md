# Swell · Connect

The sign-in and consent page used when you connect an app such as Claude to [Swell](https://github.com/robertmfreitas).
Swell's Supabase Auth (OAuth 2.1 server) sends the browser here with `?authorization_id=…`.
The only key in this page is Swell's public publishable key; row-level security protects the data.

Source of truth: `web/connect/index.html` in the Swell repo. Copy changes here to publish.
