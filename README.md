# Self-hosted WireGuard VPN

## Install

1. Copy ```docker-compose.yml``` to ```/opt/wireguard```
2. Change ```SESSION_SECRET```, ```WGUI_USERNAME```, ```WGUI_PASSWORD``` in ```docker-compose.yml```
3. Run ```docker-compose up -d``` inside ```/opt/wireguard```

## Usage
1. Open ```%YOUR_URL%:5000``` in your browser and add new client
2. Click on the ```Apply Config``` button
3. Install WireGuard app on your device and scan QR Code from UI
