## Basic Terminology for Web Development
- This section introduces fundamental terms like **Internet**, **Network**, **Browser**, **Client**, **IP Address**, **Render**, and **Browser Engine** to provide a strong foundation for the course.     

## Networks
- A **network** is a system where multiple resources, such as computers, laptops, printers, and mobile phones, are interconnected.      
- These interconnected devices can communicate, share resources, and exchange messages.    
- Networks can be either wired or wireless.   
- Networks exist at various scales:
    - **LAN (Local Area Network):** A small-scale network, typically confined to a room, home, or single building.     
    - **MAN (Metropolitan Area Network):** A network that spans across cities or states.     
    - **WAN (Wide Area Network):** A large-scale network connecting countries or continents.      

---
## Internet
- The **Internet** is a global system where billions of devices, machines, and systems are interconnected.      
- It is often described as a "network of networks," serving as a super-entity that encompasses all smaller networks.     

## World Wide Web (WWW / Web)
- The **World Wide Web** (or simply **Web**) is a system containing interconnected documents, resources, and multimedia files (like images, MP3s, and videos).    
- All these resources and documents can be accessed using the Internet.    
- The Web is considered a subset or a specific service provided by the Internet, which is a much larger entity.      

---
## IP Address
- An **IP address** is a unique identification assigned to any machine connected to a network or the Internet.      
- It is crucial for communication between two systems; one system must know the IP address of the other to send data.     
- IP addresses typically follow a format like `121.43.62.51`, where each segment contains numbers between 0 and 255.     
- More in-depth discussions on **IPv4** and **IPv6** will be covered later in the course.   

---
## Browser and Browser Engine
- A **browser** is a software application or tool that allows users to access documents, websites, web applications, and other resources available on the Internet.       
- Common examples of browsers include Google Chrome, Safari, Opera, and Mozilla Firefox.    
- A **browser engine** is the underlying "brain" of a browser, responsible for rendering (displaying) web content and running web-related applications.     
- Examples of browser engines include Blink and WebKit.   

---
## Client-Server Model
- The **Client-Server Model** describes how two machines communicate over a network, such as the Internet.    
- A **client** is a machine (e.g., laptop, mobile device, browser, or command-line interface) that initiates a request, often involving user interaction, to ask for data or a service.          
- A **server** is a machine that receives the client's request, processes it (where the logic and data are stored), and then sends back a response (output).         
- Servers can be specialized, such as database servers, file servers, application servers, web servers, or email servers.   

- Different types of requests a client can send to a server include:

| Request Type | Purpose                                     |
|:----------- |:------------------------------------------ |
| **GET**      | To fetch or retrieve data from the server.  |
| **POST**     | To create or send new data to the server.   |
| **PUT**      | To update existing data on the server.      |
| **DELETE**   | To remove data from the server.             |
    

- The **response** from the server is the output, which confirms the request's fulfillment or provides the requested data.   

---
## How a Website Loads (e.g., `www.facebook.com`)
- When a user types a domain name (e.g., `www.facebook.com`) into a client (browser), the process of loading the website begins.     
- A domain name is not a direct address; it must be converted into an **IP address**.    
- A **DNS (Domain Name System) server** performs **Domain Name Resolution**, which is the process of converting the human-readable domain name into its corresponding IP address (e.g., `121.43.62.51`).      
- Once the IP address of the server is obtained, the client sends the request to that specific server.   
- The server processes the request and sends a response back to the client. This response contains all the necessary files and logic (e.g., HTML, CSS, JavaScript) required to display the webpage.      
- Finally, the browser receives the response and **renders** (displays) the website on the user interface.     
- For example, when `google.com` loads, the server's response dictates the white color of Google, the rounded search bar, icon placements, and blue link colors.      
