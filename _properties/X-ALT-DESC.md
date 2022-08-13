---
description: Provides an alternate format for the DESCRIPTION property (an HTML body).
example: X-ALT-DESC;FMTTYPE=text/html:<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2//EN"><HTML><BODY><a
  href="msteams:/l/chat/0/0?users=EMAIL" target="_blank">LinkText</a></BODY></HTML>
references:
  - https://docs.microsoft.com/en-us/openspecs/exchange_server_protocols/ms-oxcical/d7f285da-9c7a-4597-803b-b74193c898a8
type: TEXT
clients:
  google-web:
    - description: Sanitizes dangerous HTML tags including custom protocol links.
  outlook-desktop:
    - description: Sanitizes dangerous HTML tags but not custom protocol links.
  owa:
    - description: Sanitizes dangerous HTML tags including custom protocol links.
  teams-desktop:
    - description: Sanitizes dangerous HTML tags but not custom protocol links.
---
