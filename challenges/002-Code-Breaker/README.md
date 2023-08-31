# Challenge 002: Code Breaker

[SHA256](https://emn178.github.io/online-tools/sha256.html) 
is a cryptographic hash function that outputs 256-bit value (which is called *digest*) based on input bytes.

Here is an example (which you can try using the online SHA256 generator I've linked),
```
sha256("I love pie") = 282f03100a57d71c840e8baa16ca6d418718fcd10e51a7030cb6a954c6192044
```
where the output is in hex number.

**Objective**: You are given a safe with 6-digit passcode.
You know that the safe hashes the passcode using SHA256,
and you know that the hexdigest (that is, hexadecimal representation) of
the passcode (in hexadecimal bytes, so like 00 00 00 00 00 00) is:
*b9b244d5dfa4ddc2f80a13e89c82fbc9540d51601b4ee7d6afbf92382ace221b*.

Find the code.

(Note that this is **not** how you are supposed to store passwords for your server! You need to use salting!)


## Info
* Topics: Cryptographic library (such as openssl), (for) loops
* Difficulty: Looping might be easy, but using cryptographic libraries might be a bit trickier.
