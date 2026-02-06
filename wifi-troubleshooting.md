 Wi-Fi Not Working Troubleshooting
 Issue
 
Connected to Wi-Fi but no internet access.

 Steps Tried
1. Restarted router + laptop
2. Checked IP configuration:
   ipconfig
3. Renewed IP:
   ipconfig /release
   ipconfig /renew
4. Flushed DNS:
   ipconfig /flushdns
5. Ping test:
   ping 8.8.8.8
   ping google.com

Fix
Internet restored after IP renew + DNS flush.

Tools Used
- ipconfig, ping
