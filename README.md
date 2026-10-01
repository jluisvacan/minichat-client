# 💻 MiniChat Client - Frontend

[![Frontend Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JavaScript%20(ES6+)-blue.svg)](#tech-stack--frontend-architecture)
[![QA Scope](https://img.shields.io/badge/QA-UI%20Manual-green.svg)](#qa--testing-strategy)


Welcome to **MiniChat Client**, the web interface for the [MiniChat Service](https://github.com/jluisvacan/minichat). Built with lightweight HTML5, CSS3, and native JavaScript, this repository serves as both the functional user interface.

---

## 🚀 About the Project

**MiniChat Client** handles real-time message sending, event listening, and state rendering from the `minichat` backend engine. It provides an intuitive web interface where users can send messages, view active chat logs, and monitor connection status.

### Core Capabilities
* **Real-time DOM Updates:** Renders incoming and outgoing messages dynamically without page reloads.
* **Backend Communication:** Connects seamlessly with the `minichat` server via HTTP endpoints / WebSockets.
* **Input State & Validation:** Handles empty payload prevention, UI field trimming, and interactive submit buttons.

---

## 🛠 Tech Stack & Frontend Architecture

| Component | Technology / Framework |
| :--- | :--- |
| **Frontend Stack** | HTML5, CSS3, JavaScript |
| **Backend Integration** | REST APIs / WebSockets (connecting to `jluisvacan/minichat`) |

---


### 2. Environment Setup

Clone the repository and execute services:

```bash
git clone https://github.com/jluisvacan/minichat-client.git
cd minichat-client

# Execute MiniChat Service

# Install Live Share extension in VSCode (Recommended)

# Start local development server
# Use Go Live if you install Live Share extension

# Access the service at address
http://localhost:5500
```