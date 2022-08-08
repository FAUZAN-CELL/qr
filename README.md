# qr
## Pemindai Kode QR untuk Masuk Hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```
<button onclick="window.location='https://fauzan-cell.github.io/qr';">Kode QR</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="QR Code Scanner" disabled=no dst-host=fauzan-cell.github.io
```

### Powered by FAUZAN-CELL
