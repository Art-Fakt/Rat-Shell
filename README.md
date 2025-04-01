# Rat-Shell
Rat-Shell is a "C2-Ish" Stage 0 Framework with lot of enhanced functionalities and a collaborative TeamServer targeting Windows or Unix systems.

### !!!!!!!!!!!!!!   UNDER ACTIVE DEVELOPPEMENT    !!!!!!!!!!!!!!!!!!

Still in developpement, Rat-Shell is a C2 in python3 which can handle multiple connexions on a Teamserver. You can configure multiples listeners and generate corresponding agent to initiate connexions from remote host. Severals advanced initial access methods are implemented & easily configurable.

###### Types of handlers :
  - HTTP/HTTPS
  - TCP
  - UDP
  - DNS

For every handlers you have the possibility to create multiples one-liners as agent or files with differents methods of encoding & obfuscation if needed. 
Multiples loading & injecting methods depending on targeted system.
More on these features after...

#### Main functionnalities:
  ###### Command 🎮           Description 📜
  ========             ==============
 ```bash 
  help         [+]     Print this message.
  connect      [+]     Connect with a sibling server.
  generate     [+]     Generate shell scripts.
  bff                  Print others BFF servers.
  sessions             Print established shell sessions.
  interact             Interact with an established session.
  sockets              Print Ratshell related running services' info.
  redirectors  [+]     List and manage traffic redirectors.
  shell        [+]     Enable an interactive pseudo-shell for a session.
  download     [+]     Download chosen file/folder from a session in Downloads folder.
  exec         [+]     Execute a local file or command against a session.
  open         [+]     Open a file locally directly from a session.
  modify       [+]     Open a file locally from a session and save the modified version in same place 
	               on remote session when you close file locally.
  alias        [+]     Set an alias for a shell session.
  exit                 Kill all sessions and quit.
  ```		
  		
  ###### Post-Ex Commands 🔥
  =================
  ```bash
  nodeshell    [+]     Launch a NodeJS Shell against a shell session and attempt to bypass UAC (see help)
  pyramid      [+]     Pyramid Integration.
  injectpwsh     [+]     Craft PowerShell in-memory loaders from .NET assemblies and native binaries and execute it on session filelessely.
  getsystem   	       Get a NT-AUTHORITY/SYSTEM Shell (Need to have a medium integrity user's session)
  exec-pc      [+]     PC Integration Test...
  exec-pwshx   [+]     PowerShx Integration
  reg                  Have fun with victim's Windows registry.
  aceshark     	
  ```	
		
  ###### Pivoting Commands
  =================
  ```bash	
  socks    [+]    Create Reverse Socks Proxy on victim's host.
  ligolo   [+]    Create VPN Tunnel with last version of Ligolo-ng client.
		
  ->     [+]    Local Port Forwarding.
  <-     [+]    Remote Port Forwarding.
  ```
		
  ###### Servers Commands
  ===============
  ```bash	
  start-updog	  Start the Updog file server. 🐶
  stop-updog      Stop the Updog file server.
  synergy         Start Synergy-Https GET/POST Requests server in a new terminal.
  ```
  ###### Shell commands 🥷
  ======================
  ```bash	
  upload    [+]     Upload files into an active shell session.
  inject    [+]     Fileless exec of local scripts over http.
  ```

  ###### Available Modules Commands
  =====================
  	
  All modules command begin with run.
		
  ###### Command 🎮             Modules Description 📜
  ========               ====================  
  ```bash
  run check      [+]     Run the AV/EDR Check & Exclusions (WINDOWS ONLY) 
  run lsenum     [+]     Run LinuxSmartEnumeration Script (UNIX ONLY)
  run les        [+]     Run LinuxExploitSuggester Script (UNIX ONLY)
  run peass      [+]     Run Peass-NG (UNIX & WINDOWS)
  run lpe        [+]     Run the Local PrivEscalation 1/2 (UNIX & WINDOWS)
  run dumper     [+]     Run the SAM Dumper (WINDOWS ONLY)
  ```
ANd many others options/functionnalities to come...
Possibility to enhance functionnalities with easy python3 scripting integration.

Will publish complete documentation.
