# tr_checkout

## Overview

This code is a demonstration of creating one time transactions using the
Braintree transparent redirect API.  We decided to use the
[web.py](http://webpy.org/) framework because its simplicity
allows us to clearly demonstrate concepts without added noise.

## Getting Started

To run the exmaple:

* pip install braintree
* pip install web.py
* Update checkout.py with your merchant_id, public_key and private_key
* python checkout.py
* Visit [http://localhost:8080/payments/new](http://localhost:8080/payments/new)

