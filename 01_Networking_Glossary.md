# 💾 Networking_Glossary :-

---

# 📚 A to Z of Computer Networks: Short & Sweet Reference

A quick guide to the essential terms, devices, and concepts in computer networking.

---

## 1. 🔌 Connecting Devices

-   **🔷 Bridge:** Connects two separate **Local Area Networks (LANs)** that use the same protocol. It filters traffic, meaning data from one side only goes to the other if it is destined for a device there. It helps reduce unnecessary traffic.
    -   *Example:* Connecting the LAN in the Engineering department to the LAN in the Sales department so they can share resources but keep their own internal traffic separate.

-   **🔀 Switch:** An intelligent, multi-port device that connects devices **within the same network** (like a LAN). It learns the addresses of connected devices and sends data **only** to the intended recipient, not to every port.
    -   *Example:* The box in your office that all the desktop computers are plugged into.

-   **🚦 Router:** Connects **different networks** together (e.g., your home network to the internet). It directs (routes) data packets between them, acting like a traffic cop.
    -   *Example:* The device your Internet Service Provider (ISP) gives you to connect your home WiFi network to the worldwide internet.

-   **🔄 Repeater:** Receives a signal, cleans it (removes noise), amplifies it, and retransmits it. It is used to extend the physical range of a network by overcoming signal degradation (attenuation).
    -   *Example:* A repeater placed halfway down a long office corridor to ensure the WiFi signal reaches the conference room at the far end.(If you have a signal strength = x then the Repeater can boost it to only 2x).

-   **📡 Hub:** A simple, "dumb" multi-port device that connects devices in a network. It receives data on one port and **broadcasts** it to **all** other ports. This creates a lot of unnecessary traffic and is inefficient.
    -   *Example:* An older, basic network connector. Hubs have been largely replaced by switches.

-   **🔊 Amplifier:** Similar to a repeater, but used mainly for **analog signals**. It boosts the strength of the signal, but it also amplifies any noise along with it.
    -   *Example:* Used in long-distance telephone lines or cable TV networks to boost the signal so it can travel farther.(if you have a signal strength = x then the amplifier can boost it to 2x,3x,4x,...).

---

## 2. 🧪 Signal Technologies

-   **⚫ Baseband:** A transmission method where the **entire bandwidth** of the cable is used to transmit **only one signal** at a time (usually digital). Ethernet networks use baseband transmission.
    -   *Example:* A single-lane road that can only carry one type of vehicle at a time.

-   **🌈 Broadband:** A transmission method where the bandwidth of the cable is divided into multiple **channels**, allowing many different signals (data, voice, video) to be sent simultaneously (usually analog).
    -   *Example:* A multi-lane highway with separate lanes for cars, trucks, and buses. Your cable internet uses broadband.

---

## 3. 📦 Multiplexing

-   **🧲 Multiplexer (MUX):** A device that combines **multiple input signals** from different sources into **one single output signal** for transmission over a single line.
    -   *Example:* In a large office, a multiplexer combines the phone lines from 100 desks into a single cable that goes to the telephone company.

-   **🔓 Demultiplexer (DEMUX):** A device that does the opposite of a multiplexer. It receives a **single combined signal** and separates it back into its **original, separate signals** at the receiving end.
    -   *Example:* At the telephone company's office, a demultiplexer receives that single cable and separates it back into 100 individual phone lines.

---

## 4. 🧵 Transmission Media

-   **Description:** This is the physical path or medium through which data travels from one device to another. It can be wired or wireless.
-   **🔌 Cables (Wired Media):**
    -   **Twisted Pair Cable:** Copper wires twisted together to reduce interference. Used in most homes and offices (Ethernet cables). *Cheap and common.*
    -   **Coaxial Cable:** A single copper core with better shielding than twisted pair. Used for cable TV and older networks. *Better range and less interference.*
    -   **Fiber Optic Cable:** Transmits data as pulses of light through thin glass strands. Used for high-speed, long-distance backbones. *Very fast, secure, and immune to electrical interference.*
-   **📶 Wireless Media (Unbounded):**
    -   Transmits data through the air using electromagnetic waves (Radio, Microwave, Infrared).

---

## 5. 💻 Computers & Networks

-   **💾 Standalone Computer:** A computer that is **not connected** to any other computer or network. It operates independently and cannot share resources with others.
    -   *Example:* An old PC in a basement used only for playing offline games, with no internet or network connection.

-   **🖥️ Types of Computers:**
    -   **Workstation:** A powerful computer designed for technical or scientific applications (e.g., for graphic design, video editing).
    -   **Server:** A computer that provides services (like web pages, email, or files) to other computers (clients) on a network.
    -   **Client:** A computer that requests services or resources from a server.
    -   **Mainframe:** A large, powerful computer used by large organizations for critical applications, bulk data processing.

-   **🌐 Network:** An interconnection of two or more autonomous computers and devices to share resources and data.

-   **📝 Network Description:** A detailed explanation of a network's layout, including its:
    1.  **Scope:** PAN, LAN, MAN, WAN.
    2.  **Topology:** How devices are arranged (Bus, Star, Ring, Mesh).
    3.  **Protocols:** The rules they use to communicate (TCP/IP, Ethernet).
    4.  **Components:** The devices involved (routers, switches, cables).

-   **🗺️ Types of Networks (by size):**
    -   **PAN (Personal Area Network):** Very small, for one person. (Bluetooth earbuds & phone).
    -   **LAN (Local Area Network):** A single building. (Office network).
    -   **CAN (Campus Area Network):** A university campus or business park.
    -   **MAN (Metropolitan Area Network):** A city. (City-wide public WiFi).
    -   **WAN (Wide Area Network):** Countries/World. (The Internet).

---

## 6. ⚙️ Network Services & Their Types

These are the functions or resources that a network provides to its users.

-   **📄 File Services:** Allows users to share, store, and transfer files over the network.
    -   *Example:* Google Drive, a company's shared network drive (like the `S:` drive).
-   **🖨️ Print Services:** Allows multiple users to share a single printer over the network.
    -   *Example:* Sending a document to the "Network Printer in Room 101" from your laptop.
-   **📧 Communication Services:** Enables users to communicate with each other.
    -   *Example:* Email (SMTP), instant messaging (WhatsApp), video conferencing (Zoom).
-   **🌍 Application Services:** Runs software for clients, so they don't need to install it locally.
    -   *Example:* A web server hosting a website or a database server running a CRM system for the sales team.

---

## 7. 🧩 Network Topology (The Shape of the Network)

This describes the physical or logical arrangement of devices in a network.

-   **Bus Topology:** All devices are connected to a single central cable (the "bus" or backbone). *Simple but a break in the cable can bring down the whole network.*
-   **Star Topology:** All devices are connected to a central device, like a switch or hub. *Very common. If one cable fails, only that device is affected.*
-   **Ring Topology:** Each device is connected to two other devices, forming a circular path for signals. *Data travels in one direction. A break can disrupt the whole ring.*
-   **Mesh Topology:** Every device is connected to every other device. *Highly redundant and reliable, but very expensive and complex to set up.*
-   **Tree Topology:** A combination of bus and star topologies. Groups of star-configured networks are connected to a linear bus backbone.

---

## 8. 📏 Network Protocols (The Rules)

A protocol is a set of rules and standards that two devices follow to communicate with each other. It's like a language.

-   **🌐 TCP/IP (Transmission Control Protocol/Internet Protocol):** The fundamental protocol suite for the internet. IP handles addressing and routing, TCP ensures reliable data delivery.
-   **🏠 Ethernet:** The most common set of rules for wired LANs (IEEE 802.3 standard).
-   **📶 Wi-Fi:** The common set of rules for wireless LANs (IEEE 802.11 standard).
-   **📧 SMTP (Simple Mail Transfer Protocol):** Used for sending emails.
-   **🌍 HTTP/HTTPS (Hypertext Transfer Protocol / Secure):** Used for transferring web pages on the internet.
