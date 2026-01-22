<h2>Reverse Shell Notes</h2>

<b>❌ Not Recommended</b><br>
Webshell → Backconnect Webshell → Reverse Shell (Netcat + Ngrok)<br><br>

<b>✅ Recommended</b><br>
rs.php → Reverse Shell → VPS<br><br>

<b>🐚 Spawn TTY (Interactive Shell)</b><br>
<code>python3 -c 'import pty; pty.spawn("/bin/bash")'</code><br>
