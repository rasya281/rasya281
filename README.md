authtoken: 21MjeHAquzuwtTlERdAJ0wW0FmR_4WGzg9y3NLZHoFVDaV5rg
log: ngrok.log
tunnels:
  first:
    addr: 3000
    proto: http
    bind_tls: true
  second:
    addr: 8000
    proto: http
    bind_tls: true
  third:
    addr: 9999
    proto: http
    bind_tls: true
