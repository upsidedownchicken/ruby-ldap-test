# Ruby LDAP Connection

Repo for messing around with [ruby-net-ldap](https://github.com/ruby-ldap/ruby-net-ldap). Default connection params are for [this online test server](https://www.forumsys.com/tutorials/integration-how-to/ldap/online-ldap-test-server/).

To run it, copy `.env.example` to `.env`, edit as needed, and:

```
$ env $(cat .env | xargs) ./ldap
```
