# Radicale IMAP

IMAP authentication plugin for [Radicale](http://radicale.org/).

## Installation

```shell
$ python3 -m pip install --upgrade https://github.com/Unrud/RadicaleIMAP/archive/master.tar.gz
```

## Configuration

```ini
[auth]
type = radicale_imap

# IMAP server hostname
# Syntax: address
# Syntax: address:port
# Syntax: [address]:port
# For example: imap.server.tld
#imap_host =

# Secure the IMAP connection
# Value: tls | starttls | none
#imap_security = tls

# Domains allowed separated with comma
# Syntax: domain[,domain]
#    note: values are separated with comma
# Default: ""
#    note: empty value allow all domains to authenticate
#allowed_domains = domain.tld, other.domain.org
```

## License

[GPL-3.0](https://github.com/Unrud/RadicaleIMAP/blob/master/COPYING)
