````md
# SEZAR - Uzbek Latin Alphabet Caesar Cipher Library

**SEZAR** is a Python library that implements the Caesar Cipher encryption algorithm for the Uzbek Latin alphabet. This library allows easy encryption and decryption of text, supporting both Uzbek letters and special characters. The library is specifically designed for the Uzbek language using the Latin alphabet.

## Installation

Installing the **SEZAR** library is simple and can be done with `pip`. To install, run the following command:

```bash
pip install SEZAR
````

## Usage

### Encryption

You can encrypt a text using the `cipher` function provided by the library. Here's an example of encrypting a text with a `key=3`:

```python
from SEZAR import cipher

plaintext = "Salom Dunyo"
key = 3

encrypted = cipher(plaintext, key)
print(encrypted)  # Output: "Vdorp Gwqbr"
```

### Decryption

To decrypt the encrypted text, use the `decipher` function. Here's an example:

```python
from SEZAR import decipher

encrypted = "Vdorp Gwqbr"
key = 3

original = decipher(encrypted, key)
print(original)  # Output: "Salom Dunyo"
```

### `key` Parameter

* The `key` parameter is the shift used for encryption and decryption. For example, with `key=3`, each letter will be shifted 3 positions to the right in the alphabet.

## Project Description

**SEZAR** implements the Caesar Cipher algorithm for the Uzbek Latin alphabet. It supports all characters of the Uzbek Latin alphabet as well as special characters such as `O'`, `G'`, `SH`, `CH`, and `NG`.

The supported characters are:

* All letters of the Uzbek Latin alphabet (`A`, `B`, `C`, ..., `Z`)
* Special characters (`O'`, `G'`, `SH`, `CH`, `NG`)

## Requirements

* Python 3.7 or higher.
* The library supports only the **Uzbek Latin Alphabet**.

## License

MIT License. All rights reserved.

## Author

**Author**: Raxmonqulov Diyorjon Ulug'bek o'g'li
**Email**: [coderdiyorjon0624@gmail.com](mailto:coderdiyorjon0624@gmail.com)

## Support

If you have any questions or issues related to this library, please feel free to contact the author via the email address: **[coderdiyorjon0624@gmail.com](mailto:coderdiyorjon0624@gmail.com)**

## Contributing

If you'd like to contribute to the **SEZAR** library, feel free to submit a pull request. We appreciate all contributions!

1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

```

### Description:
- **Installation**: in this part, the method of installing the library using `pip` is explained in English.
- **Usage**: in the Usage section, the encryption and decryption processes are listed in English.
- **Project Description**: Description of the library, what it is designed for and how it works, is presented in English.
- **License**: MIT License is referenced in English.
- **Support**: users are informed about how to contact if they have questions.

```
