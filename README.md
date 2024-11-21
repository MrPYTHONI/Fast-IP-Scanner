

https://github.com/user-attachments/assets/88723277-e0dd-41cd-b074-26719eca05bf

# **Fast-IP-Scanner** 🕵️‍♂️🚨

**Fast-IP-Scanner** is a **super-fast**, **multi-threaded** tool for scanning **IP ranges** and **domains**. Whether you're hunting down **Cloudflare** or **Varnish** protected servers, or scanning an entire IP range, this tool makes you the **ultimate hacker**. ⚡

Get ready to penetrate networks and **unmask hidden servers** with a hacker-themed interface that will leave you feeling like a **cyber ninja**. 💻💥

---

### **Features**:

- **🔍 Super Fast Scanning**: Scans IP ranges and domains in **record time** using multi-threading.
- **⚡ Cloudflare & Varnish Detection**: Automatically detects and logs servers behind **Cloudflare** or using **Varnish**.
- **📁 Output Results to File**: Save scan results to **output files** for easy review.
- **💀 Hacker-Style Interface**: Engages the user with a **rich, hacker-like interface**, including **colorful text effects**.
- **🛠️ Customizable**: Define the number of **threads** and **ports** for the scan.

---

### **How to Use:**

1. **Clone the Repository:**

```bash
git clone https://github.com/your-username/Fast-IP-Scanner.git
cd Fast-IP-Scanner

2. Install Dependencies:



pip install -r requirements.txt

3. Run the Scanner:



To scan IPs or domains from a file and save the results:

python Fast-IP-Scanner.py -if input_file.txt -o output_file.txt

To scan a specific IP range:

python Fast-IP-Scanner.py --file ranges.txt -o output_file.txt



---

Command Options:

-if: Specifies the file containing IP addresses or domain names.

-o: Output file to save the scan results.

--threads: The number of concurrent threads (default: 500).

--port: Port to scan (default: 80).

--file: Optionally specify a file with IP ranges or addresses for scanning.



---

Example Usage:

Scanning from a file and saving results:

python Fast-IP-Scanner.py -if input_file.txt -o results.txt

Scanning an IP range:

python Fast-IP-Scanner.py --file ranges.txt -o results.txt



---

Additional Features:

CIDR Notation Support: Fast-IP-Scanner can handle CIDR ranges like 192.168.1.0/24, converting them into individual IPs for scanning.


Example of CIDR scanning:

python Fast-IP-Scanner.py --file cidr_ranges.txt -o results.txt


---

Contribute:

Feel free to contribute! Fix bugs, add features, or improve documentation. Open a pull request or report any issues.


---

Requirements:

Python 3.x

aiohttp

rich (For rich, hacker-like output)



---

License:

This project is licensed under the MIT License.


---

Social Links:





---

Become the Hacker You Always Wanted to Be 💻💥

Step into the world of network penetration. Fast-IP-Scanner is here to let you scan IPs, unmask servers, and test networks like a pro hacker.


---

Disclaimer:

Fast-IP-Scanner is intended for ethical and educational use only. Ensure you have permission before scanning any networks or servers.

---

---

Official Developer: MrPYTHON

Telegram: https://t.me/PYT_HON3

Portfolio: https://mrpython3.carrd.co/
