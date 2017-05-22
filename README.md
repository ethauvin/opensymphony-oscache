Modified version of [OpenSymphony's OSCache](https://bitbucket.org/opensymphony/oscache/) with support for automatically generating keys that take in consideration the server port (HTTP, HTTPS).

To enable add the following to `oscache.properties`:

```ini
cache.use.host.domain.in.key=true
```

