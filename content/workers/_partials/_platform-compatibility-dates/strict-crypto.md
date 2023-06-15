---
_build:
  publishResources: false
  render: never
  list: never

name: "Strict crypto error checking"
# sort date increased by 2, noCfBotManagementDefault and strictCompression have
# the same compatibility date but was added earlier.
sort_date: "2023-08-03"
enable_date: "2023-08-01"
enable_flag: "strict_crypto_checks"
disable_flag: "no_strict_crypto_checks"
---

Perform additional error checking in the Web Crypto API to conform with the specification. Additionally, reject key parameters that may be unsafe based on the modulus or key length.