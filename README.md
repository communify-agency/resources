# Commands

## Spider and download website

```
wget -m -p -E -k -H -Dsomedomain.com somedomain.com
```

wget options:

  * `-m` mirror site - equivilent to:
    * `-r` recursive
    * `-N` time-stamping to prevent re-downloading files later
    * `-l inf` infinite levels
  * `-p` download page requisites
  * `-E` adjust file extensions
  * `-k` convert links
  * `-H` span hosts (see -D below to include hosts)
  * `-D` include domains. Include original domain plus any other domains, such as cloudfront cdn assets like `-Dmydomain.com,cloudfront.com`

