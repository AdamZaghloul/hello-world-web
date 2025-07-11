# hello-world-web
To test hosting a simple webapp using cloudflare tunnels

## Deployment Steps:

1. Make sure go mod version is in line with rpi: go mod edit -go=1.19
2. Build the app: go build .
3. Run the binary in the background: nohup ./hello-world-web &
