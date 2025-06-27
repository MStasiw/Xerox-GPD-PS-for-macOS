# Xerox-GPD-PS-for-macOS
Automating the installation/addition and configuration of two virtual pull print type print queues which connect to Windows Print Server hosted shared print queues which function with an Equitrac Office 5.6 environment.
Creates two CUPS based printers, one for each Virtual Follow-You Print Queue
- CAPTRBW : Virtual Follow-You Print Queue for printing in Black/White (Greyscale)
- CAPTRCLR : Virtual Follow-You Print Queue for printing in Colour

Development of custom full-featured PPD files/CUPS print driver, one for each of these print queues, to preset and restrict printer options shown in macOS print UI.
This will avoid need for Equitrac Workstation Client/Document Routing CLient (DRC) software installation and licensing. Example situation when have a restricted/locked down environment which does not allow installing additional client software.

Virtual print queue is a pull print type queue which in Windows uses Pull Printing feature enabled through Xerox Pull Print Driver PS and integration with Equitrac Office 5.6 multi-server installation.for a Xerox generic/universal/model independent set of features available on the most common models in printer fleet, differentiated by one for mono/BW only printing and other for colour printing.

Note: On macOS cups all built-in/Apple provided/Xerox provided PPD files are printer model specific. There does not exist one universal/model independent PPD or equivalent to the Xerox Global Print Driver (GPD) PostScript (PS) for Windows OS.
