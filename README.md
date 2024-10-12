Phonakuma

Phonakuma is an open-source project inspired by Pwnagotchi, but with a unique twist. Unlike Pwnagotchi, Phonakuma is designed to not only sniff Wi-Fi signals but also cellular signals. Phonakuma gives you the ability to sniff SMS messages and analyze cellular networks in your area, making it a powerful tool for understanding and exploring mobile phone networks.

Key Features

Cellular Signal Sniffing: Phonakuma can sniff cellular signals, including SMS messages transmitted through the 2G, 3G, 4G, and 5G LTE networks. It utilizes compatible USB dongles that support these cellular standards.

Mobile Network Mapping: Phonakuma allows users to map out and learn about mobile phone networks within their region. By using compatible USB dongles, the device collects data on nearby cellular towers and infrastructure.

Cellular Infrastructure Identification: Phonakuma identifies various cellular towers in the user's region. It provides detailed information, such as cellular identifiers (Cell IDs), location, GPS coordinates, and more.

Tower and Provider Information: The device uses public databases to display characteristics of cellular towers. It provides information such as:

Carrier/Provider Information: Details about which carriers are using a specific cellular tower.

Shared Infrastructure: Identifies if multiple cellular carriers are using the same tower infrastructure.

Geolocation Data: GPS coordinates and other location-based data for cellular infrastructure.

Compatible Hardware: Phonakuma supports 2G, 3G, 4G, and 5G LTE USB dongles, which are essential for capturing and analyzing cellular data.

Use Cases

Mobile Network Analysis: Analyze mobile network coverage and infrastructure in your area.

Learning Tool: Understand how mobile networks are deployed and how they interact with devices.

Carrier Research: Gather information on different carriers and their shared infrastructure.

Getting Started

Hardware Requirements

Raspberry Pi or similar SBC (Single Board Computer)

Compatible USB cellular dongles (2G, 3G, 4G, 5G LTE)

GPS module (optional but recommended for precise geolocation)

Software Requirements

Python 3.x

Necessary libraries for USB modem interaction (e.g., pyserial)

Linux-based OS (preferably a Debian-based distribution like Raspbian or Ubuntu)

Installation

Clone the repository:

git clone https://github.com/yourusername/phonakuma.git
cd phonakuma

Install dependencies:

sudo apt-get update
sudo apt-get install -y python3 python3-pip
pip3 install -r requirements.txt

Set up the hardware by connecting compatible USB dongles and optional GPS modules.

Run the Phonakuma script:

python3 phonakuma.py

Disclaimer

Phonakuma is intended for educational and research purposes only. The developers are not responsible for any misuse of the software. Always ensure you comply with your local laws and regulations regarding cellular data interception and analysis.

Contributions

Contributions are welcome! Feel free to fork the project and submit pull requests.

License

Phonakuma is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Inspired by Pwnagotchi

Built with love by contributors around the world.
