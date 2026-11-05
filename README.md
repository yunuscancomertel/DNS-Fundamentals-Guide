# 🌐 DNS & Network Fundamentals Guide

Welcome to the **DNS & Network Fundamentals** repository. This repository is dedicated to documenting core network protocols, their operational mechanics, and their crucial role in cybersecurity and Security Operations Center (SOC) analysis.

---

## 📌 Executive Summary

Understanding core network protocols like **DNS (Domain Name System)** is essential for any aspiring SOC Analyst or Cyber Defense Specialist. Before diving into complex SIEM log analysis or threat hunting, mastering how system communications work at the foundational level is critical.

This guide breaks down DNS resolution, its fundamental architecture, and why it serves as a key telemetry source during security investigations.

---

## 🔍 Core Concepts: What is DNS?

The **Domain Name System (DNS)** functions as the "address book" of the Internet. While humans remember domain names (e.g., `google.com`), computer systems interact via IP addresses (e.g., `142.250.185.78`). 

* **Domain Name:** Human-readable alias.
* **IP Address:** Machine-readable numerical identifier.
* **DNS:** The protocol that bridges names to IP addresses.

---

## 🔄 Basic Resolution Flow

1. **Client Request:** The browser checks the local cache. If missing, it queries a Recursive Resolver.
2. **Recursive Search:** The resolver queries Root, TLD, and Authoritative Name Servers.
3. **Response & Connection:** The final IP address is returned to the client, establishing a direct connection.

---

## 📝 Featured Article

I have published a detailed, beginner-friendly guide covering DNS mechanics and foundational network concepts on Medium.

👉 **[Read the Full Article on Medium](https://yunuscancomertel.medium.com/your-internet-guide-what-is-dns-and-how-does-it-work-for-absolute-beginners-c7a6ce424353)**

---

## 🔗 Connect & Network

* **LinkedIn:** [Yunus Can Cömertel](https://www.linkedin.com/in/yunuscancomertel)
* **Medium:** [@yunuscancomertel](https://yunuscancomertel.medium.com/)

---
*Created as part of my ongoing cybersecurity and SOC analysis learning roadmap.*
