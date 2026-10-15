===================================================================
cURL 7.60.0 Portable Package for Tru64 UNIX V5.1B (Alpha)
===================================================================

1. DESCRIPTION
Portable cURL binary package built natively for Tru64 UNIX V5.1B (Alpha).
Includes OpenSSL 1.1.1 static libraries and zlib for modern HTTPS/TLS 1.2+ support.

2. CONTENTS
- curl-portable/bin/curl
- curl-portable/lib/libssl.a, libcrypto.a, libz.so.1
- curl-portable/share/cacert.pem

3. EXTRACT / RESTORE
Run the following command as root:

 cd /usr/local
 gzip -d -c /usr/users/user01/curl-tru64-5.1b-portable.tar.gz | tar xvf -
