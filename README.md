# fido2-tests

Test suite for FIDO2, U2F for testing an [implementation](https://github.com/pmvr/micropython-fido2/tree/master) on a Pyboard

# Setup

Need python 3.6+.

`make venv` and `source venv/bin/activate`

Or simply `pip3 install --user -r requirements.txt`

# Running the tests

Run all FIDO2, U2F, and HID tests:

```
pytest tests/standard -s
```

# License

Apache-2.0 OR MIT

