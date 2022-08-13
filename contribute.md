---
layout: page
title: Contribute
---

## Structure

Each proprietary property is defined in a file in the [`_properties/`] folder named as `<property name>.md`, such file consists only of a [YAML] front matter which describes the binary and its clients.

The full syntax is the following:

```
---
---
description: Description of the property.
example: Code of the example.
references:
- URL of reference.
type: Property value data type as specified in https://www.rfc-editor.org/rfc/rfc5545#page-30.
clients:
  CLIENT:
    - description: Description of how the client handles this property.
---
```

Where `CLIENT` is one of the values described in the [`_data/clients.yml`] file.

Feel free to use any file in the [`_properties/`] folder as an example.

## Pull request process

Properietary properties are accepted as well as non-standard implementations of standard properties. Any limitations or quirks shall be noted in the `description` field.

Before sending a pull request of a new property or client, ensure that the property is implemented as described in the client.

Pull requests adding new clients in [`_data/clients.yml`] are allowed and subjected to project maintainers vetting.

[YAML]: https://yaml.org/
[`_properties/`]: https://github.com/spaceraccoon/icalendardb/tree/main/_properties
[`_data/clients.yml`]: https://github.com/spaceraccoon/icalendardb/blob/main/_data/clients.yml
