# Kraken - Web Interface Survey Tool
Kraken is a tool to help make your web interface testing workflow more efficient. This is done by using Django, Apache, and a MySql database to store and organize web interface screenshots and data. This allows you and your team to take notes and track which hosts have been tested simultaniously. Once you are finished, you can view these notes you took and generate reports in the Reports section. 

## Quick Start

Clone the repository down and run the following commands (Note, don't clone into /opt or it won't install correctly):

```# chmod 755 setup.sh```

```# ./setup.sh```

You will be asked to supply a TCP port to host Kraken on. The default port is 8000. The setup script will ensure that your system is not using the port selected before proceeding.

Once setup is complete, open your browser and visit http://localhost:<port> and use the following default credentials to log in:

admin:2wsxXSW@

User management functionality can be found at http://localhost:8000/admin

##  Detailed Installation Steps, Usage, and Troubleshooting

Please visit the [wiki](https://github.com/Sw4mpf0x/Kraken/wiki) for more detailed information. 

https://pentestarmoury.com/2017/01/31/kraken-web-interface-survey-tool/
