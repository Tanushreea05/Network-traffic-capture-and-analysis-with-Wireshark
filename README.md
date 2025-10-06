# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:

- Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1914" height="1076" alt="image" src="https://github.com/user-attachments/assets/f411f844-fbc1-4a90-8c97-de526b72eb61" />


- **Start Capturing Packets**

• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/756d9bed-6559-4a1b-8a52-a172d9333d17" />


- **Apply Filters to Focus on Specific Traffic**
  
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/a8a01e01-af36-44b4-b3d9-0cea3c9f9948" />


- **Analyze Packet Details**
  
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.

<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/b0fe85f4-8da4-438e-8630-04df7204c8bb" />
<img width="1878" height="345" alt="image" src="https://github.com/user-attachments/assets/8428deed-5f0f-4716-b27f-f153f461c453" />


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
