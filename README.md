# myqr
## QR Code scanner

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://galanter.github.io/scan';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Mikhmon QR Code Scanner" disabled=no dst-host=galanter.github.io
```

### Powered by webqr.com
