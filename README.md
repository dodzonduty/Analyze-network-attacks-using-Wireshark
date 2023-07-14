# Analyze-network-attacks 
<h2> Description </h2>
I work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, I received an automated alert from the monitoring system indicating a problem with the web server. I attempted to visit the company’s website, but I received a connection timeout error message in my browser.
<h2>Project process</h2>
I used a packet sniffer(WireShark) to capture data packets in transit to and from the web server. I noticed a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. I suspected that the server is under a "DOS" attack by a malicious actor.<br>
<a href="Wireshark TCP_HTTP log - TCP log.pdf"> Wireshark TCP_HTTP log </a><br>
after furhter analysis of the log it was time to write an incident report about the attack.<br>
<a href="Network attack incident report .pdf"> Incident report</a>

