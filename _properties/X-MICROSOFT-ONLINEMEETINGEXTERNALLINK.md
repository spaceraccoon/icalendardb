---
description: The OnlineMeetingExternalLink element is an optional element that contains a URL for an online meeting.
example: X-MICROSOFT-ONLINEMEETINGEXTERNALLINK:https://meet_url.example.com/
references:
  - https://docs.microsoft.com/en-us/openspecs/exchange_server_protocols/ms-ascal/6367d2cb-3dc8-4797-8b29-3f5b5fd7278f
type: TEXT
clients:
  owa:
    - description: Sanitizes non-HTTP protocols.
  teams-desktop:
    - description: Displays link as-is in join meeting.
---
