Apache Bench
=============

[![](https://images.microbadger.com/badges/image/alishaikh/ab.svg)](https://microbadger.com/images/alishaikh/ab "Get your own image badge on microbadger.com")

A Docker image that contains Apache Bench.

### Usage

Run Apache Bench against a URL:

- `docker run alishaikh/ab ab -k -n 10000 -c 16 http://<URL-HERE>/`