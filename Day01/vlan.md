## ✅ VLAN Summary (Basic Level)

### 🔹 What is a VLAN?

A **VLAN (Virtual Local Area Network)** is a way to **logically divide a physical network** into smaller, isolated sections.
Even if devices are connected to the same switch, they can be **separated into different networks** using VLANs.

---

### 🔹 Why is it used?

* To **separate departments or traffic types** (e.g., HR, Finance, Guest Wi-Fi)
* To **improve security** by isolating sensitive traffic
* To **reduce broadcast traffic** and improve performance
* To **support multiple networks on a single physical switch or link**

---

### 🔹 Real Example

A company uses:

* **VLAN 10 → HR Department**
* **VLAN 20 → Finance Department**
* **VLAN 30 → Guest Wi-Fi**

Even though all devices are connected to the **same switch**, users in one VLAN **can’t talk to** users in another VLAN unless the network is specifically set up to allow it.

---

### 🔹 Access vs Trunk Ports

| Port Type       | Purpose                            | VLANs                           |
| --------------- | ---------------------------------- | ------------------------------- |
| **Access Port** | Connects to end devices like PCs   | 1 VLAN only                     |
| **Trunk Port**  | Connects switches, routers, or APs | Carries multiple VLANs (tagged) |
  *trunk port id identifies sender

---

### 🔹 How does it work with Wi-Fi?

In large setups, wireless **Access Points (APs)** broadcast multiple **SSIDs** (like `Corp-WiFi`, `Guest-WiFi`):

* Each **SSID is assigned to a different VLAN**
* The **AP tags traffic** from each SSID with the correct VLAN ID
* The AP is connected to the switch using a **trunk port** so it can send **all VLANs over one cable**

---
