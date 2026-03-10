# Network Intrusion Detection System Using Scapy

A Network Intrusion Detection System (NIDS) is used to monitor network traffic and identify 
potential security threats such as attacks, unauthorized access, or suspicious behavior. With the 
increasing use of the internet, network security has become very important. This project 
focuses on building a basic NIDS that can analyze packets and generate alerts using Python. 
 
The main objectives of this project are: 
• To capture live network packets 
• To analyze TCP and UDP traffic 
• To detect suspicious packets using rules 
• To generate alerts for possible intrusions 
• To provide a user-friendly GUI for monitoring 

## Installation

1. Clone the repository:
   
       git clone https://github.com/<Your-Username>/Network-Intrusion-Detection-System-Using-Scapy.git
   
2. Navigate into the project directory:
   
        cd Network-Intrusion-Detection-System-Using-Scapy
   
3. Install the required dependencies:

               pip install -r requirements.txt
   


## Usage

1.Run the intrusion detection system:
  
       python src/nids.py

2.Add custom detection rules using the following format:

       action protocol src_ip src_port flow dst_ip dst_port message

## License
This project is licensed under the MIT License - see the LICENSE file for details.
