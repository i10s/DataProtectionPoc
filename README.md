# DataProtection PoC
Proof of concept using IDataProtectionProvider

This Process is easier for developers to use solid Cryptographic algorithm to make safe their data in the case you need to encrypt/decrypt your data frequently.

With this,

If you need to encrypt data, simply pass the data into the protect method.
If you need to access the data again, pass the encrypted data into the Unprotect method, and it will be converted back into plaintext.

## Usage

### Protect
```bash
http://localhost:5000/protect/[string to protect]
```

### Unprotect
```bash
http://localhost:5000/unprotect/[string protected]
```


