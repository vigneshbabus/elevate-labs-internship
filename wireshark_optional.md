Wireshark Analysis (Optional)

I used Wireshark to analyze packets during my Nmap scan.  
I applied this filter to see SYN packets:

tcp.flags.syn == 1 and tcp.flags.ack == 0

This helped me observe how Nmap detects open ports by watching packet responses.
