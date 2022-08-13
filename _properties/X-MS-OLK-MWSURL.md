---
description: Specifies the URL of the Meeting Workspace.
example: X-MS-OLK-MWSURL:https://mws-host.com/mws
references:
  - https://docs.microsoft.com/en-us/openspecs/exchange_server_protocols/ms-oxcical/89ac6ed4-cf58-42a6-a618-8ed26ec0b073
type: TEXT
clients:
  outlook-desktop:
    - description: When user responds to appoint, Outlook sends a SOAP messsage to /_vti_bin/meetings.asmx. Renders value in reminder popup as "View Meeting Workspace" link.
---
