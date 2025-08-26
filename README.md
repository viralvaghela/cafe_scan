# cafe_full_pentest.sh
Recon + Safe Exploit (default-creds / anonymous-only) for internal pentest of cafe network
# USAGE:
```sudo ./cafe_full_pentest.sh <subnet> [--exploit]```
# Eg:
```sudo ./cafe_full_pentest.sh 192.168.68.0/24 --exploit```

# IMPORTANT: Only use with written authorization explicitly permitting these tests.
# This script performs non-destructive checks only (no password spraying, no RCE payloads).

# Dependencies:
nmap, nc, curl, ffmpeg (or ffprobe), smbclient, smbmap (optional), enum4linux (optional), whatweb, nikto, snmpwalk, upnpc (miniupnpc) or gssdp-discover/avahi, jq (optional)
