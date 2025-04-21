# License Server

<figure><img src="../.gitbook/assets/license server 2025.15.png" alt=""><figcaption></figcaption></figure>

**License Server**: Requires that a Flexera based license server is running on a network that the ALM has access to. This mode supports both traditional license server and TRIAD based license servers. After the Port field is populated, click the apply button to connect to the license server. The fields in the LICENSE INFORMATION and LICENSE COUNTS groups will populate with information about the license expiration, maintenance user, company, and license features/counts.

1. License Server: The Port field is automatically populated. If desired, check the Custom Port box, and type a custom Port number for the license server.
2. TRIAD: Enter the servers as the value for the SRV\_PATH key in the [Environment Variable File](../environment-variable-file.md). Each server needs to be entered as comma separated value with no spaces. Ports are required for TRIAD&#x20;
   1. Examples:&#x20;
      1. `<port1>@<host1>,<port2>@<host2>,<port3>@<host3>` or&#x20;
      2. `<host1>:<port1>,<host2>:<port2>,<host3>:<port3>`
