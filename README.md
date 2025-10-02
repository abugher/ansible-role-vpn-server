Forward UDP ports 500 and 4500.  Give the designated host an alias of `vpn`.

So far the server end seems to run, but an android client just says "Connecting...", and nothing shows up in the server log (syslog) upon connection attempt.  There are log entries if I try to connect my phone from the LAN, but the attempt ends with `KDF_PRF with PRF_HMAC_SHA2_256 not supported`, `key derivation failed`, `found encrypted message, but no keys available`, and `IKE_AUTH request with message ID 1 processing failed` from `charon-systemd`.
