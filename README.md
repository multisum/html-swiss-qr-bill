# Swiss QR Bill in HTML

Creation of Swiss QR Bills as HTML. There is no need to send data to a server. Only HTML, CSS and JavaScript are used.

For the QR Code the QR Code generator library from Nayuki (https://github.com/nayuki/QR-Code-generator) is used.


## ChangeLog

A simple string as reference is now converted to a Creditor Reference (ISO 11649) if possible.
A Creditor Reference (ISO 11649) with an incorrect checksum is now displayed in red.

---

Version 1.6 of Nayuki's QR Code Generator is now included because the newer version is different.
