# Basic Network Scanning with Nmap

## Project Overview
This project demonstrates the use of **Nmap (Network Mapper)** to perform basic network scanning. The objective is to identify active hosts, open ports, and running services on a target system in a controlled and authorized environment.

## Objective
- Learn the basics of network scanning.
- Identify open ports and services.
- Understand how Nmap gathers network information.
- Save scan results for documentation and analysis.

## Tools Used
- Kali Linux
- Nmap
- Python 3 HTTP Server (Target)
- GitHub

## Target Information
- Target IP: `<Target_IP>`
- Operating System: Linux
- Test Service: Python HTTP Server

## Commands Used

### Check Network Interface
```bash
ifconfig
```

### Verify Target Connectivity
```bash
ping <Target_IP>
```

### Basic Nmap Scan
```bash
nmap <Target_IP>
```

### Service Version Detection
```bash
nmap -sV <Target_IP>
```

### Save Scan Results
```bash
nmap -sV <Target_IP> -oN nmap_scan_results.txt
```

## Scan Results
The scan identified:
- Active host
- Open ports
- Running services
- Service versions (where detected)

Detailed results are available in:
```
nmap_scan_results.txt
```

## Project Structure

```
Basic-Network-Scanning/
│
├── README.md
├── nmap_scan_results.txt
└── screenshots/
    ├── ifconfig.png
    ├── python_server.png
    ├── nmap_scan.png
    └── saved_results.png
```

## Screenshots
Include screenshots of:
1. Network interface (`ifconfig`)
2. Running Python HTTP Server
3. Nmap scan execution
4. Saved scan result
## Learning Outcomes
- Understood the basics of network scanning.
- Learned how to identify open ports and services.
- Practiced using Nmap command-line options.
- Documented scan results professionally.

## Conclusion

this project provided practical experience with basic network scanning using Nmap. It demonstrated how to identify active hosts, detect open ports, and gather information about running services in a controlled environment.
