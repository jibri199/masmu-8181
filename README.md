# J1BRIL99
## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```
<button onclick="window.location='https://j1bril99.github.io/adi-8181';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="QR Code Scanner" disabled=no dst-host=j1bril99.github.io
```

### Powered by webqr.com
