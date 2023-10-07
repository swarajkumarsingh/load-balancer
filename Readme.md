# Golang Round-Robin Load Balancer

This is a simple round-robin load balancer implemented in Golang. It distributes incoming HTTP requests evenly among a list of backend servers.

## Usage

1. Clone the repository:
```bash
git clone https://github.com/swarajkumarsingh/load-balancer.git
```

2. Build and run the load balancer:
```bash
go build main.go
./main
```

3. Send HTTP requests to the load balancer's endpoint (e.g., http://localhost:8080) to distribute them among your backend servers.

## Configuration
### You can configure the load balancer by modifying the main.go file. Here are the key points for configuration:
- Add or remove backend server URLs in the backendServers slice in the main function.
- You can change the port on which the load balancer listens by modifying the port variable in the main function.

## Dependencies
The load balancer uses the following Go standard library packages:
- net/http: For creating the HTTP server.
- net/http/httputil: For creating reverse proxies.
- net/url: For parsing and handling URLs.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Feel free to contribute to this project by opening issues or pull requests. Your contributions are welcome!

## Author
Swaraj kumar singh
