# JIBRI199
## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```
<button onclick="window.location='https://jibri199.github.io/masmu8181';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="QR Code Scanner" disabled=no dst-host=jibri199.github.io
```

### Powered by webqr.com

