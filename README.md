# SOCLabDeployment

<b>This lab is done using an ARM64-based Mac leveraging a virtual machine environment to demonstrate experience spinning up a home lab security operation center for analysis. The tools deployed and utilized throughout this lab are a firewall (pfSense), router (vyos), two Windows hosts, an attack box (Kali Linux), network monitoring (Arkime/Suricata), and a log aggregation tool (Elk/OpenSearch) deployed with a Sysmon agent to generate and ship telemetry for logging.</b>

<h2>STEP 1: Setting up a virtualization environment</h2>
<b>To spin up a virtualization environment, several products are to be considered. The following utilizes local resources: Parallel Desktop, Vmware, Virtual Box, and UTM. The other option is to set up a rapid-deployable cloud lab. For this lab, I used Parallel Desktop.</b>
