## What is the Internet?
- The **Internet** is fundamentally "interconnected networks," a global system where billions of devices and numerous networks are connected, enabling communication and data exchange.      

  
     

## Evolution of the Internet
- The internet's origins trace back to the **ARPANET** project in the 1960s by the Department of Defense, aiming to send data between two machines by breaking it into small chunks called **packets** to ensure data reception even with some loss during war situations.         
- By the 1970s, ARPANET's technology began to be used at organizational and institutional scales.   
- The 1980s saw the development of the **Domain Name System (DNS)**, which converts domain names into IP addresses, and the emergence of the **World Wide Web**.   
- The 1990s marked the **commercialization** of the internet, introducing email, messaging, and online shopping.    
- The 2000s brought the rise of social media platforms like Facebook and the widespread adoption of mobile phones, further evolving internet usage.   
- Today, the internet is indispensable for communication, data sharing, resource sharing, and accessing various online tools and products like YouTube.        

  
       

## Client-Server Model
- The **client-server model** describes how a client machine sends requests to a server, which processes them and sends back a response.       
- Clients can be browsers, command-line interfaces, or even the user's machine itself.    
- Servers perform operations based on the request and return an output, which could be data, an update confirmation, or a creation confirmation.    

| Request Type | Description                                                              | Example                                                              |
|:----------- |:----------------------------------------------------------------------- |:------------------------------------------------------------------- |
| **GET**      | Fetching data from the server.                                           | Client asks for "10 color names."                                  |
| **PUT**      | Updating existing data on the server.                                    | Client asks to "update the spelling of 'purple'."                |
| **POST**     | Creating new data on the server.                                         | Client asks to "add a new color named 'black'."                  |
| **DELETE**   | Removing data from the server.                                           | Client asks to "delete the color 'black'."                       |
    

## Addressing and Protocols
- To communicate with a server, a client needs to know the server's **IP address**, which acts as its unique address on the network.       
- **Protocols** are sets of rules that standardize how different tasks are performed on the internet, ensuring consistent communication (e.g., SMTP for email, HTTP for web, FTP for file transfer).            
- The **Domain Name System (DNS)** is a crucial process that converts human-readable domain names (like `www.google.com`) into machine-readable IP addresses.        
      

## How a Request Travels: ISPs, Routers, and the Protocol Stack
- When a client sends a request, it first goes to an **Internet Service Provider (ISP)**, which provides access to the internet.         
- ISPs can be local, regional, or national (Tier-1), with requests potentially being forwarded up the hierarchy if a local ISP doesn't know the destination IP address.       
- **Routers** are networking devices that connect multiple networks and forward data packets towards their destination. Requests often hop through many routers to reach the server.         
- Each router maintains a **routing table** to determine the best path for a packet; if an entry is not found, it forwards the request to its parent router.      
- Data travels in **packets**, which are small chunks of a larger file, reassembled at the destination.       
- The **protocol stack** breaks down the interaction between applications into different layers, each with specific functions:
    - **Application Layer**: Specific to the application (e.g., Gmail using SMTP).     
    - **TCP Layer**: Defines the **port number** to identify the specific application on the destination machine.     
    - **IP Layer**: Adds the **IP address** of the destination machine to the request.     
    - **Hardware Layer**: Uses the communication medium (wired or wireless) to send the data packets.   
- At the destination, the data travels back up the layers, with each layer performing tasks like re-arranging packets and checking validity.      
                  

## Homework and Further Learning
- Students are encouraged to research **IPv4** and **IPv6** to understand the syntax and evolution of IP addresses.     
- Investigate **networking devices** such as switches, hubs, routers, and modems.    
- Explore the **OSI Model** (Open Systems Interconnection) with its seven layers (Physical, Data Link, Network, Transport, Session, Presentation, Application) and the **TCP/IP Model**, which are crucial for networking interviews.      
- Search for the **DNS tree structure** to understand how domains are linked.   
- Find a command to print the IP address of a domain like `www.google.com`.
