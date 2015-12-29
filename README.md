# gosites
Serve multiple static websites via simple Go-based tool.

```
rootFolder:
  - foo.com:
    .gosite.yml
    - ssl:
        cert.pem
        key.pem
    - public:
        index.html
  - bar.com:
    - public:
        index.html
  - proxy-example.com:
      .gosite.yml // proxy: somedomain.com:8080
    - ssl:
        cert.pem
        key.pem
```
