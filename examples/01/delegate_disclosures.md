__Disclosure for `Delegate Payload (array element)`:__

```
SHA-256 Hash: wSDiixEiiUJftWeBNAwo3nDjfHBss_qUTsFpD--O-0Y
Disclosure:
WyJkZW1vLWwyLXBheWxvYWQiLHsiX3NkIjpbIjU3OU5NV0FmN0VXMUhqUEY3UXduWVRa
b3I3VXpLVlhia3hqV1cxVTNxeEEiLCIzSElYM09CZExCbloxTEhuaU9WWHU5MVZQcWFi
dTZYM1o5Q21DaXAzVWlBIl0sImNuZiI6eyJqd2siOnsiY3J2IjoiUC0yNTYiLCJrdHki
OiJFQyIsIngiOiJCSlMtcGdEUTlrenlZMXBKdXMyX2VJRnkyT3R5Q0hnazhJNkZUWE9P
WExrIiwieSI6InlEemVLWUZGaFZGWGVEbmYySkl0anUyZTBVeVVfMmlPcVhrTHUtWG5K
Rk0ifX0sInZjdCI6Imh0dHBzOi8vZXhhbXBsZS50ZXN0L3ZpL2F1dG9ub21vdXMifV0
Contents:
[
  "demo-l2-payload",
  {
    "_sd": [
      "579NMWAf7EW1HjPF7QwnYTZor7UzKVXbkxjWW1U3qxA",
      "3HIX3OBdLBnZ1LHniOVXu91VPqabu6X3Z9CmCip3UiA"
    ],
    "cnf": {
      "jwk": {
        "crv": "P-256",
        "kty": "EC",
        "x": "BJS-pgDQ9kzyY1pJus2_eIFy2OtyCHgk8I6FTXOOXLk",
        "y": "yDzeKYFFhVFXeDnf2JItju2e0UyU_2iOqXkLu-XnJFM"
      }
    },
    "vct": "https://example.test/vi/autonomous"
  }
]
```

__Disclosure for `payment_mandate`:__

```
SHA-256 Hash: 579NMWAf7EW1HjPF7QwnYTZor7UzKVXbkxjWW1U3qxA
Disclosure:
WyJkZW1vLXBheW1lbnQtc2FsdCIsInBheW1lbnRfbWFuZGF0ZSIseyJhbGxvd2VkX3Bh
eWVlcyI6WyJtZXJjaGFudC5leGFtcGxlLnRlc3QiXSwiY25mIjp7Imp3ayI6eyJjcnYi
OiJQLTI1NiIsImt0eSI6IkVDIiwieCI6IkJKUy1wZ0RROWt6eVkxcEp1czJfZUlGeTJP
dHlDSGdrOEk2RlRYT09YTGsiLCJ5IjoieUR6ZUtZRkZoVkZYZURuZjJKSXRqdTJlMFV5
VV8yaU9xWGtMdS1YbkpGTSJ9fSwicGF5bWVudF9hbW91bnQiOnsiY3VycmVuY3kiOiJK
UFkiLCJtYXhfYW1vdW50IjoxNTAwMH0sInZjdCI6Im1hbmRhdGUucGF5bWVudC4xIn1d
Contents:
[
  "demo-payment-salt",
  "payment_mandate",
  {
    "allowed_payees": [
      "merchant.example.test"
    ],
    "cnf": {
      "jwk": {
        "crv": "P-256",
        "kty": "EC",
        "x": "BJS-pgDQ9kzyY1pJus2_eIFy2OtyCHgk8I6FTXOOXLk",
        "y": "yDzeKYFFhVFXeDnf2JItju2e0UyU_2iOqXkLu-XnJFM"
      }
    },
    "payment_amount": {
      "currency": "JPY",
      "max_amount": 15000
    },
    "vct": "mandate.payment.1"
  }
]
```

__Disclosure for `checkout_mandate`:__

```
SHA-256 Hash: 3HIX3OBdLBnZ1LHniOVXu91VPqabu6X3Z9CmCip3UiA
Disclosure:
WyJkZW1vLWNoZWNrb3V0LXNhbHQiLCJjaGVja291dF9tYW5kYXRlIix7ImFsbG93ZWRf
aXRlbXMiOlt7Im1heF9xdWFudGl0eSI6Miwic2t1IjoiU0tVLUJPT0stMDAxIn1dLCJh
bGxvd2VkX21lcmNoYW50cyI6WyJtZXJjaGFudC5leGFtcGxlLnRlc3QiXSwiY25mIjp7
Imp3ayI6eyJjcnYiOiJQLTI1NiIsImt0eSI6IkVDIiwieCI6IkJKUy1wZ0RROWt6eVkx
cEp1czJfZUlGeTJPdHlDSGdrOEk2RlRYT09YTGsiLCJ5IjoieUR6ZUtZRkZoVkZYZURu
ZjJKSXRqdTJlMFV5VV8yaU9xWGtMdS1YbkpGTSJ9fSwidmN0IjoibWFuZGF0ZS5jaGVj
a291dC4xIn1d
Contents:
[
  "demo-checkout-salt",
  "checkout_mandate",
  {
    "allowed_items": [
      {
        "max_quantity": 2,
        "sku": "SKU-BOOK-001"
      }
    ],
    "allowed_merchants": [
      "merchant.example.test"
    ],
    "cnf": {
      "jwk": {
        "crv": "P-256",
        "kty": "EC",
        "x": "BJS-pgDQ9kzyY1pJus2_eIFy2OtyCHgk8I6FTXOOXLk",
        "y": "yDzeKYFFhVFXeDnf2JItju2e0UyU_2iOqXkLu-XnJFM"
      }
    },
    "vct": "mandate.checkout.1"
  }
]
```
