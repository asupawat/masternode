# STAMP Masternode Installer
Autoinstaller for STAMP Masternode on Ubuntu 16.04 VPS. This script will install your STAMP node on a clean Ubuntu 16.04 VPS. If you already have any other wallets running, please check firewall ports. You can only install one STAMP masternode per VPS.

If you don't have a VPS yet, please choose a small Ubuntu 16.04 virtual machine at <a href="https://www.vultr.com/?ref=7476040" rel="nofollow">vultr.com</a></p>

Prepair VPS:
<pre><code>
wget https://raw.githubusercontent.com/zSAM-Project/masternode/master/vps_setup.sh && sudo chmod 755 vps_setup.sh && ./vps_setup.sh
</pre></code>

1 MN:
<pre><code>
wget https://raw.githubusercontent.com/zSAM-Project/masternode/master/stamp_mn_install.sh && sudo chmod 755 stamp_mn_install.sh && ./stamp_mn_install.sh
</pre></code>

3 MN in 1 VPS:
<pre><code>
wget https://raw.githubusercontent.com/zSAM-Project/masternode/master/stamp_3mn1vps_install.sh && sudo chmod 755 stamp_3mn1vps_install.sh && ./stamp_3mn1vps_install.sh
</pre></code>
License
Released under the MIT license.

Disclaimer
Developer assume no liability and is not responsible for any misuse or damage caused by this program.
