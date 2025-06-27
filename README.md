# Xerox-GPD-PS-for-macOS
Automating the installation/addition and configuration of two virtual pull print type print queues which connect to Windows Print Server hosted shared print queues which operate in a Pull Print workflow in conjunction with a solution such as Equitrac Office 5.6.
Creates two CUPS based printers, one for each Virtual Follow-You Print Queue
- CAPTRBW : Virtual Follow-You Print Queue for printing in Black/White (Greyscale)
- CAPTRCLR : Virtual Follow-You Print Queue for printing in Colour

Development of custom full-featured PPD files/CUPS print driver, one for each of these print queues, to pre-set and restrict printer options shown in macOS print UI.
This will avoid need for Equitrac Workstation Client/Document Routing CLient (DRC) software installation and licensing. Example situation when have a restricted/locked down compute environment/policy which does not allow installing additional client software.

Virtual print queue is a pull print type queue which in Windows uses Pull Printing feature enabled through Xerox Pull Print Driver PS and integration with Equitrac Office 5.6 multi-server installation. Also acts like the Xerox Global Print Driver (GPD) PostScript (PS).

Requiring a Xerox generic/universal/model independent set of features to be presented to end users, offering only the features (such as finishing options: staple, hole punch, tray selection) on the most common printer models in customer's printer fleet.

Note: In CUPS all built-in/Apple provided/Xerox provided PPD files are printer model specific/model dependant. There does not exist one universal/model independent PPD or equivalent to the Xerox Global Print Driver PS as there is for Windows OS.
