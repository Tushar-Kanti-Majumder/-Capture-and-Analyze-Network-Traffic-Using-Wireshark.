# -Capture-and-Analyze-Network-Traffic-Using-Wireshark.
Installed and Started Wireshark: I installed Wireshark on my system and launched it to begin capturing network traffic on my active network interface.

Captured Traffic: I started the capture and browsed the web by searching for Sachin Tendulkar on Google and later visited YouTube to generate network traffic.

Filtered for TCP Traffic: After about 1 minute of browsing, I stopped the capture and used the TCP filter (tcp) in Wireshark to isolate and analyze TCP-based protocols.

Identified 3 TCP Protocols: I identified and analyzed three different TCP-based protocols:

    HTTP (Port 80) for the Google search request.

    HTTPS (Port 443) for the secure connection to YouTube.

    DNS over TCP (Port 53) for resolving domain names like www.google.com.

Documented Findings: After filtering and analyzing the packets, I exported the capture file and summarized my findings, detailing the different TCP protocols observed during my browsing session.
