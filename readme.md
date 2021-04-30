# FMEA (Flexible Modifiable Encryption Algorithm)

A flexible **EXPERIMENTAL** Encryption algorithm with `FNNH` hash algorithm (a Hashing algorithm i made earlier) with used defined block size decleration and data size dependent Encryption.

## **WARNING: This is a Experimental Encryption Algorithm**

### HOW TO USE

1. Run the Command `pip install FMEA` in your python ENV.
2. and to use the algo write :
```python
from FMEA import FMEA

plain_text = "qwerty"
password = "123"
streass = 1
blocksize = 64

#mode = 1 is for encrypting the data
cipher_text = FMEA(plain_text,password,mode=1,blocksize,stress)

#mode = 2 is for encrypting the data
plain_text = FMEA(ciphertext,password,mode=2,blocksize,stress)

```
