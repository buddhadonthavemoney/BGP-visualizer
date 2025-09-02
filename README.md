# **BGP Protocol Visualization**

An interactive P5.js animation that demonstrates the core principles of the Border Gateway Protocol (BGP), focusing on AS\_PATH construction and best path selection.  
*(Replace the placeholder above with a screenshot or GIF of your animation\!)*

## **Description**

This project provides a visual, interactive way to understand how Autonomous Systems (AS) on the internet share routing information. Users can click on an AS to make it advertise a new network prefix and watch as the advertisement propagates through the network. The simulation clearly shows how each AS builds its Routing Information Base (RIB) and selects the shortest AS\_PATH as the best route to a destination.

## **How to Use**

1. Clone or download this repository.  
2. Open the bgp\_animation.html file in any modern web browser.  
3. Click on the grey circles (Autonomous Systems) to start a route advertisement.  
4. Hover over packets and overflow indicators (...) to see more details.  
5. Click the "Reset Simulation" button to start over.

## **Features**

* **Interactive Topology:** Click on any AS to originate a route.  
* **Real-time Propagation:** Watch advertisement packets travel between peers.  
* **Detailed RIB Display:** Each AS shows its learned prefixes, the active best path (in green), and alternative paths (in grey).  
* **Overflow Handling:** Cleanly handles complex scenarios with tooltips to show full routing tables.  
* **Responsive Canvas:** The animation adapts to your browser window size.  
* **Self-Contained:** Runs entirely in a single HTML file with no external dependencies besides P5.js from a CDN.

## **Technologies Used**

* **P5.js:** For the canvas and animation logic.  
* **HTML & CSS:** For the page structure and styling.