# The Tiny Encryption Algorithm.
**Version:** `0.2`

## Reference:
```python
>>> tea_encrypt(b'barbecue', b'\xb6\xb6\xb9\xf8Mj\xba\x0c\x91\x7f\t\x1e\xbe\xcc\xb1\xd0')
b'\xe7v\xfd\x02\x8cj\xef\xc1'
>>> tea_decrypt(b'\xe7v\xfd\x02\x8cj\xef\xc1', b'\xb6\xb6\xb9\xf8Mj\xba\x0c\x91\x7f\t\x1e\xbe\xcc\xb1\xd0')
b'barbecue'

>>> xtea_encrypt(b'american', b'Q\xaf\xc6\x17\xb5<\xd4\xc8\xfa\x0c\x88\xca\x95_\x9aV')
b'd\x01:\x0e\x93\xce\x8c8'
>>> xtea_decrypt(b'd\x01:\x0e\x93\xce\x8c8', b'Q\xaf\xc6\x17\xb5<\xd4\xc8\xfa\x0c\x88\xca\x95_\x9aV')
b'american'
```

## License:
* [MIT License](LICENSE.md)
