# legendary
Random code snippets to assist security programming and automation


Inorder to run this portscanner.py

1)Run a netcat to listen to either tcp or udp:

  TCP- netcat -v -l -t -p 5555
  UDP- netcat -v -l -u -p 5555
  
2) Script usage:

  TCP- python PortScanner_udp.py -a localhost -p 5555

  UDP- python PortScanner_udp.py --udp -a localhost -p 5555
