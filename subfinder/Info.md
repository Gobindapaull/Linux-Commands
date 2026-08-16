# subfinder

- sudo apt update
- sudo apt install golang-go
- go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
- export PATH="$PATH:$(go env GOPATH)/bin"
- subfinder -version 
- subfinder -d domain_name -o subdomains.txt
