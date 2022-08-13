---
description: Link to Skype or Teams meeting.
example: |
 X-MICROSOFT-SKYPETEAMSMEETINGURL:https://teams.microsoft.com/l/meetup-join/
  19%3ameeting_MmQ0MjI1ZjMtMjE0Yi00ZTY4LThmYmMtZmY3NmUzMDMyOWQ2%40thread.v2/
  0?context=%7b%22Tid%22%3a%225d08b37c-b698-400d-b333-9e8b32140464%22%2c%22O
  id%22%3a%227bc64f55-9f35-46ea-8ea3-fa03d7c84914%22%7d
references:
type: TEXT
clients:
  teams-desktop:
    - description: Displays in Join button and Right Click Join context menu; doesn't seem to have protocol sanitization.
  outlook-desktop:
    - description: Displays in join and hover; doesn't seem to have protocol sanitization.
  owa:
    - description: Shows up as join meeting link in  web app but must be HTTP protocol.
---
