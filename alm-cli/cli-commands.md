# CLI Commands

You can always run:

```
.\ApexLM_CLI.exe -h
```

to see a list of available commands from within the terminal

<figure><img src="../.gitbook/assets/ApexLM_CLI.exe -h.png" alt=""><figcaption></figcaption></figure>

* **manage \<install | reset | delete | shutdown >**
  * ApexLM\_CLI.exe manage install
    * Installs Trusted Storage for APEX OpenCode licenses. Will cause a restart of the Apex LM.
  * ApexLM\_CLI.exe manage reset
    * Reset Trusted Storage licenses for APEX Trusted Storage
  * ApexLM\_CLI.exe manage delete
    * Delete Trusted Storage licenses for APEX Trusted Storage
  * ApexLM\_CLI.exe manage shutdown
    * Shutdown the ApexLM application



* **generate \<activation | update | return>**
  * ApexLM\_CLI.exe generate activation
    * Generate an OpenCode activation request code for APEX Trusted Storage
  * ApexLM\_CLI.exe generate update
    * Generate an OpenCode update request code for the current activation for APEX Trusted Storage. Used for updating the maintenance expiration date.
  * ApexLM\_CLI.exe generate return
    * Generate OpenCode return request code for the current activation for APEX Trusted Storage



* **process**
  * ApexLM\_CLI.exe process
    * Process an activation or deactivation OpenCode response code from the APEX User Site activation for APEX Trusted Storage



* **cancel**
  * ApexLM\_CLI.exe cancel
    * Cancel a current activation, update, or return request for APEX Trusted Storage



* **display \<options | licenses | logs | status | fulfilments | records | costs>**
  * ApexLM\_CLI.exe display options
    * Display the ApexLM options and values on the console
  * ApexLM\_CLI.exe display licenses
    * Display the ApexLM license information and counts on the console
  * ApexLM\_CLI.exe display logs
    * Display contents of the ApexLM log file on the console
  * ApexLM\_CLI.exe display status
    * Display the ApexLM OpenCode status information for APEX Trusted Storage on the console
  * ApexLM\_CLI.exe display fulfilments
    * Display the ApexLM OpenCode license fulfilment information for APEX Trusted Storage on the console
  * ApexLM\_CLI.exe display records
    * Display the ApexLM license records information request for APEX Trusted Storage on the console
  * ApexLM\_CLI.exe display costs
    * Display the ApexLM cost list information request for APEX Trusted Storage on the console



* **export \<mode | licenses | fulfilments | records | costs>**
  * ApexLM\_CLI.exe export mode
    * Export the ApexLM options and values to text file
  * ApexLM\_CLI.exe export licenses
    * Export the ApexLM license information to text file
  * ApexLM\_CLI.exe export fulfilments
    * Export the ApexLM OpenCode license fulfilment information for APEX Trusted Storage to text file
  * ApexLM\_CLI.exe export records
    * Export the ApexLM license records information request for APEX Trusted Storage to text file
  * ApexLM\_CLI.exe export costs
    * Export the ApexLM cost list information request for APEX Trusted Storage to text file



* **options \<mode | licpath | srvpath | port>**
  * ApexLM\_CLI.exe options mode
    * Switch the licensing mode between Node-Locked License File, License Server, and APEX OpenCode
  * ApexLM\_CLI.exe options licpath
    * Set the Node-Locked license file path
  * ApexLM\_CLI.exe options srvpath
    * Set the hostname and port for license server
  * ApexLM\_CLI.exe options port
    * Set the port for the ApexLM application. Will cause a restart of the Apex LM.
