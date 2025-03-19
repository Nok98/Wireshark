# Title: "Wireshark Traffic Analysis Lab"

**Objective**: To capture and analyze different network traffic types (DNS, ICMP, and HTTP).

**Tools Used**: Wireshark

**Description:**
In this lab, I captured and analyzed network traffic including DNS queries, ICMP echo requests/replies (ping), and HTTP traffic. Filters were used to isolate specific packet types for detailed analysis. This helped me understand network protocols and packet flow.

**Captured Traffic:**

ICMP Traffic:

Captured ICMP packets representing a ping request and response between devices. This type of traffic helps monitor network connectivity.
Filter used: icmp
Screenshot Description: Displays the ICMP packets showing the request and reply process, confirming successful communication between devices.
DNS Traffic:

Captured DNS query and response packets, which show how the client (your computer) sends a request to a DNS server to resolve a domain name (e.g., "example.com") to an IP address.
Filter used: dns
Screenshot Description: Shows the DNS request for a domain name resolution and the DNS response with the resolved IP address.
HTTP Traffic:

Captured HTTP request and response headers, which demonstrate how data is transferred over the web. This includes the request sent by the client (browser) and the response returned by the web server.
Filter used: http





