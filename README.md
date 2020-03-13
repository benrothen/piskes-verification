# Tamarin-based Verification of PISKES
Verification part of the paper "PISKES: Pragmatic Internet-Scale Key-Establishment System" that has been presented
at AsiaCCS 2020.

In the file `first-order-exchange.spthy` a highly abstracted version of the key exchange between two ASes is modeled.
Timestamps are modeled using nonces and only a single key epoch is considered.

In the file `second-order-request.spthy`, the model is refined with multiple key epochs. Additionally, the exchange
between AS and end host is modeled as well.

### Credits
- Main work by Dominik Roos ([Oncilla](https://github.com/Oncilla/))
- Thanks to Ralf Sasse, Joel Wanner and Dennis Jackson for help with the verification and suggestions for improvements

