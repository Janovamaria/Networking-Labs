# Network Troubleshooting

## Objective

To understand common network issues, troubleshooting techniques, and basic networking commands used to diagnose and resolve connectivity problems.

## What is Network Troubleshooting?

Network troubleshooting is the process of identifying, diagnosing, and resolving problems that affect network connectivity and communication between devices.

## Common Network Issues

* No Internet Connection
* Incorrect IP Configuration
* DNS Resolution Failure
* DHCP Issues
* Slow Network Performance
* Cable or Hardware Failure
* Router or Switch Failure
* Firewall Blocking Traffic

## Basic Troubleshooting Steps

1. Check physical connections (cables, ports, Wi-Fi).
2. Verify IP address configuration.
3. Test connectivity using the `ping` command.
4. Check DNS resolution.
5. Verify default gateway configuration.
6. Restart network devices if necessary.
7. Review firewall settings.
8. Check router or switch status.

## Common Networking Commands

### Ping

Tests connectivity between two devices.

```bash
ping google.com
```

### ipconfig (Windows)

Displays IP configuration information.

```bash
ipconfig
```

### ifconfig / ip addr (Linux)

Displays network interface configuration.

```bash
ifconfig
```

or

```bash
ip addr
```

### tracert (Windows)

Displays the path packets take to reach a destination.

```bash
tracert google.com
```

### traceroute (Linux)

Displays the route packets travel.

```bash
traceroute google.com
```

### nslookup

Checks DNS name resolution.

```bash
nslookup google.com
```

### netstat

Displays active network connections and listening ports.

```bash
netstat
```

## Skills Learned

* Network Troubleshooting
* Connectivity Testing
* DNS Troubleshooting
* IP Configuration
* Basic Network Diagnostics
* Networking Commands

