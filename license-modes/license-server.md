# License Server

<figure><img src="../.gitbook/assets/license server 2025.15.png" alt=""><figcaption></figcaption></figure>

**License Server**: Requires that a Flexera based license server is running on a network that the ALM has access to. This mode supports both traditional license server and TRIAD based license servers.&#x20;

<figure><img src="../.gitbook/assets/license server window 2025.15 (1).png" alt=""><figcaption></figcaption></figure>

After the host field is populated, click the apply button to connect to the license server. The fields in the LICENSE INFORMATION and LICENSE COUNTS groups will populate with information about the license expiration, maintenance user, company, and license features/counts.

1. License Server: Type the host name and port of the license server into the host field. If no port is specified in the license file, then only the host name or IP address is required. However, if a port is specified, you must enter both the host and port in one of the following formats:&#x20;
   1. `<port>@<host>` or&#x20;
   2. `<host>:<port>`
2. TRIAD: Use either the same formats as license server, but each server needs to be entered as comma separated with no spaces. Ports are required for TRIAD. Examples:
   1. `<port1>@<host1>,<port2>@<host2>,<port3>@<host3>` or&#x20;
   2. `<host1>:<port1>,<host2>:<port2>,<host3>:<port3>`
