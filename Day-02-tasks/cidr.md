🔹 What is CIDR?

CIDR (Classless Inter-Domain Routing) is used to allocate IP addresses efficiently.

🔹 Format
IP/CIDR
Example: 192.168.1.0/24
/24 → network bits
Remaining bits → host
🔹 Formula
Total IPs = 2^(32 - CIDR)

Examples:

/24 → 256 IPs
/16 → 65536 IPs
🔹 Why CIDR?
Saves IP addresses
Used in cloud (VPC)