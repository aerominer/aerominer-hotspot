# AERO MINER Hotspot

![aerologodoc-01](https://user-images.githubusercontent.com/100297185/155962059-a418abff-7856-414b-be4b-dffec867efed.png)

AERO MINER Hotspot is a product developed by Ecas Electro whose main activity is the distribution of electronic components. Ecas Electro was founded in 1991 having as main activity the sales of electronic components, electro- mechanical devices, modules, subsystems and various materials used in production, maintenance and service. 
# Company Information
Ecas Electro SRL is a Romanian based company with over 31 years of experience in this field and a turnover of approximately $ 3 million per year and over 15 million in the last 5 years according to the statistics provided by the 2 profile sites: https://lege5.ro/Firma/ecas-electro-srl-2596172 and https://www.risco.ro/verifica-firma/ecas-electro-cui-2596172 .
	During Over the 31 years of activity we have had a wide range of products/services delivered to the market (e.g. electronic components, electro- mechanical devices, modules, subsystems and various materials used in production, maintenance and service) with a lot of satisfied partners including: TDK, Microchip, Digi, Mean Well, Maxim Integrated, Silicon Labs, Texas Instruments, Siretta, Digilent, Treston, etc.
	Ecas Electro is certified ISO9001, ISO14001, OHSAS 18001 to provide products, services and solutions to industrial and commercial users of electronic components.
	We can also provide you with a virtual tour of our factory if you wish, for an overview of our equipment and production line.
For rapid development of products, to be launched on the market, is offered to our clients a wide range of development tools and software hardware structures for applications that include real-time operating systems, testing environments, debugging and compiling programs, libraries application programs, programmers, modules for test and development boards, technical assistance, information about products offered, seminars and symposium for the promotion of new products. 
	Also, since 2012, our company has started putting effort in the development and manufacture of hardware products.
	At the same time, to assist manufacturers of electronic equipment, Ecas Electro have a partnership with Felix Electronic Services (www.felix-ems.ro) an inhouse company of ECAS, owned by the same shareholders.  We are able to execute prototypes and series of electronic modules using modern technologies. Customers and other electronics designers can check their projects based on a large variety of components provided by our company, and then can order executions of large series.
# Product Information
AERO Miner Hotspot, compatible with Helium network, contains high quality and radio performances, resilient and secure gateway, based on the same hardware and software architecture, with a 8-channels LoRaWAN modem (Semtech Reference design v1 and v2 depending on models), a worldwide bands 4G modem and 10/100 ethernet controller.
All gateways come in 868MHZ variants, and support EU868, LoRaWAN regional parameters.
# Customer Support
AERO Miner has a worldwide 24/7 support teams based in Romania.
# Hardware Security

![683c36bd-812c-45c6-afdd-e224c5ca29af](https://user-images.githubusercontent.com/100297185/155962555-bdeab259-1d5d-4bfb-a601-769dcd95103e.jpg)
![86384fc0-7a34-4f02-b0fe-d00e552232ea](https://user-images.githubusercontent.com/100297185/155962564-0029a50b-39ef-4a9b-8415-9dd9af439f93.jpg)

AERO Miner gateways have an embedded hardware security built in the CPU, provided by ProvenCoreTM and based on ARM TrustZone. The behavior is very similar to an ECC chip and is the same for all Kerlink products independently with the full miner or light miner version (iZeptoCell & iBTS products have equivalent security integration as the ones already running with the full miner). This has a dedicated processing and storage unit that can store secrets and process security functions (signature, encryption) using private keys. The key is stored ciphered in a hardware memory that is not reachable from the Linux Kernel or userland. Even if the hardware is physically compromised, the key cannot be recovered. When the hardware performs signatures or encryptions, the key is never loaded into the RAM.
When the firmware signature verification is enabled, the bootloader will refuse to load the firmware unless the signature matches the key burned in the CPU. The CPU has 4 slots of keys that are fuses, and one slot can be erased in the event of key compromising.
The bootloader itself cannot be modified (locked).
Kerlink can provide more information upon demand and is willing to comply to any third-party audit.
Kerlink gateways can be configured to be monitored by the WanesyTM Management Center (WMC) software. This is a cloud-based SaaS that enables remote gateway management (OTA firmware upgrade, configuration change, monitoring, KPIs, supervision, alarms, etc.). The connection between the gateways and the WMC is secured by an OpenVPN connection. The OpenVPN certificate and private key are stored in the ProvenCoreTM hardware security module. The key is never reachable from the Kernel or userland and cannot be compromised. TLS and security negotiation for the VPN are handled by ProvenCoreTM so that the key is never loaded into the RAM.
Kerlink gateways can remotely self-configure using a provisioning server called WanesyTM Operational Assistant (WOA). The gateways have a private key generated in production and download a certificate (PKCS10) from WOA to authenticate themselves. This provides TLS client-based and server-based mutual authentication. Provisioning information that WOA may send (OTA, configuration, etc) are securely transmitted only to the gateway authorized and authenticated for it.
Kerlink is using this security to store the swarm_key, generated in production. WOA save the public key part of the swarm key and never store the private key. The gateway can authenticate on WOA during the onboarding procedure, to generate the add_gateway transaction and provide it to WOA. WOA then provide it to the phone wallet app once ownership of the gateway by the phone wallet app has been identified (like a QR code on the gateway). The wallet app signs the transaction. The onboarding procedure for light miner is the same as the full miner procedure. The onboarding server retrieve the swarm public key from WOA, the transaction from the blockchain and can sign the add_gateway transaction. The private swarm key never leaves the gateway, is never stored by Kerlink, and it cannot be recovered since it is stored ciphered in the hardware security memory.
# Manufacturing Information
Kerlink Group is a leading global provider of connectivity solutions for designing, launching, and operating public & private Internet of Things networks. Its comprehensive product portfolio includes industrial-grade network equipment, best-of-breed network core, operations and management software, value-added applications and expert professional services, backed by strong R&D capabilities. Kerlink specializes in enabling future-proof intelligent IoT connectivity for three major domains: Smart Cities – metering, parking, street lighting, waste management, air quality & pollution, building & facilities, assets monitoring… Smart Industries – fleet & asset tracking, energy & utilities, oil, gas & mining, airports, harbors, infrastructure, manufacturing, retail… and Smart Territories – precision agriculture, environment protection and rural towns & areas. More than 120,000 Kerlink installations have been rolled out with more than 330 clients in 69 countries. Based in France, with subsidiaries in the US, Singapore, India, and Japan, Kerlink is a co-founder and board member of the LoRa Alliance® and the uCIFI Alliance™. It is listed on Euronext Growth Paris under the symbol ALKLK.
# Budget & Capital
Kerlink SA is a stable public company, listed at Euronext Growth, Paris stock exchange.
All financial information are public:
https://live.euronext.com/en/ipo-showcase/kerlink
# Other Information
- Desired Discord support channel name: aerominer#4079
- Twitter profile: https://twitter.com/aero_miner
- Website: https://aero-miner.com
- Payment methods available: - 
- Regions covered / shipped to: Europe
