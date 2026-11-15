# Mission 7 — How Computers Communicate

## 1. Mission title
Mission 7 — How Computers Communicate

## 2. Task / objective
The objective was to understand basic computer networking concepts, observe network connectivity and DNS lookup information, and explain what happens when a user opens a website.

## 3. Work completed

- Studied LAN, MAN, WAN, DNS, Router, Protocol, Packet Switching and Client-Server.
- Tested network connectivity using `ping`.
- Performed a DNS lookup using `nslookup`.
- Explained the process of opening a website in six steps.

### Network Concepts

| Concept | Explanation | Example |
|---|---|---|
| LAN | Connects devices within a small area. | Home or office network |
| MAN | Connects networks across a city or large campus. | City-wide network |
| WAN | Connects networks over large geographical areas. | Internet |
| DNS | Translates domain names into IP addresses. | Resolving example.com |
| Router | Connects networks and forwards data. | Wi-Fi router |
| Protocol | Rules used by devices to communicate. | HTTP and HTTPS |
| Packet Switching | Divides data into packets for transmission. | Internet data transfer |
| Client-Server | A client requests a service and a server provides it. | Browser requesting a webpage |

### Network Observations

**Connectivity test**

Command used:
`ping -c 4 example.com`

Observations:
- Packets transmitted: 4
- Packets received: 4
- Packet loss: 0%
- Average response time: 5.948 ms

This test showed that my computer could successfully reach the example website during the test.

**DNS lookup**

Command used:
`nslookup example.com`

Observations:
- DNS resolver used: 8.8.8.8
- Domain queried: example.com
- IP addresses returned: 104.20.23.154 and 172.66.147.243

DNS lookup finds the IP address associated with a domain name. This helps a browser locate the destination server when a user enters a website name.

### What Happens When You Open a Website?

1. The user enters a website address in a browser. The browser acts as a client.
2. DNS resolves the domain name into an IP address if the address is not already available in the cache.
3. The computer sends network data through its network connection and router.
4. The browser communicates with the website server using network protocols such as HTTPS.
5. The server processes the request and sends the requested data back in packets.
6. The browser receives and processes the response, then displays the website to the user.

## 4. Commands / tools used

- `ping -c 4 example.com` — tested connectivity to a public example domain.
- `nslookup example.com` — performed a DNS lookup.
- Terminal — executed the networking commands.
- VS Code — prepared the mission documentation.

## 5. My understanding

I learned that computer networks allow devices to exchange information. LAN, MAN and WAN describe networks of different geographical sizes. DNS translates domain names into IP addresses, while routers forward data between networks. Protocols provide communication rules, and packet switching allows data to travel in smaller packets. A browser works as a client that requests information from a server.

## 6. Difficulties faced

No major difficulties.

## 7. How I resolved them

I followed the Terminal instructions, observed the command outputs and reviewed the meaning of each networking concept.

## 8. Evidence / files

- `mission-07-networking/README.md`
- Connectivity test output from `ping`
- DNS lookup output from `nslookup`

## 9. Commit details

To be updated after committing and pushing the completed mission.
