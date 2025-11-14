# Master_Setup_Instructions.md

## GCP – Google Cloud Platform Setup
- [GCP-010 Create GCP Project](./GCP/GCP-010_Create-Project.md)  
- [GCP-020 Enable Required APIs](./GCP/GCP-020_Enable-APIs.md)  
- [GCP-030 Create Service Account](./GCP/GCP-030_Create-Service-Account.md)  
- [GCP-040 Create OAuth Credentials](./GCP/GCP-040_Create-OAuth-Credentials.md)  
- [GCP-050 Create Free Tier VM](./GCP/GCP-050_Create-Free-Tier-VM.md)  
- [GCP-060 Assign Static External IP](./GCP/GCP-060_Assign-Static-IP.md)  
- [GCP-070 Set Up Firewall Rules](./GCP/GCP-070_Setup-Firewall-Rules.md)  
- [GCP-080 Connect via SSH to VM](./GCP/GCP-080_Connect-SSH-VM.md)  
- [GCP-090 Apply System Updates](./GCP/GCP-090_System-Updates.md)  

## SYS – System Configuration
- [SYS-010 Configure SSH Access](./SYS/SYS-010_SSH-Setup.md)  
- [SYS-020 Create Non Root User and Configure sudo](./SYS/SYS-020_Create-NonRoot-User.md)  
- [SYS-030 Install Essential Packages](./SYS/SYS-030_Install-Packages.md)  
- [SYS-040 Install and Verify Tailscale](./SYS/SYS-040_Tailscale-Setup.md)  

## DOCK – Docker Environment
- [DOCK-010 Install Docker Engine](./DOCK/DOCK-010_Install-Docker.md)  
- [DOCK-020 Verify Docker Group Permissions](./DOCK/DOCK-020_Verify-Permissions.md)  
- [DOCK-030 Install Docker Compose](./DOCK/DOCK-030_Install-Docker-Compose.md)  
- [DOCK-040 Test Docker Installation](./DOCK/DOCK-040_Test-Hello-World.md)

## GIT - GitHub 
- [GIT-010_Setup_FineGrainedToken_SingleRepo](./GIT/GIT-010_Setup_FineGrainedToken_SingleRepo.md) 

## N8N – n8n Setup and Integrations
- [N8N-010 Base Installation](./N8N/N8N-010_Base-Install.md)  
- [N8N-020 Reverse Proxy with SSL](./N8N/N8N-020_Reverse-Proxy.md)  
- [N8N-090 Google Sheets Connector](./N8N/N8N-090_Google-Sheets-Connector.md)  
- [N8N-095 Slack Connector](./N8N/N8N-095_Slack-Connector.md)  
- [N8N-100 Email Notifications](./N8N/N8N-100_Email-Notifications.md)  
- [N8N-110 Backup and GitHub Sync](./N8N/N8N-110_Backup-and-GitHub-Sync.md)  

## MSC - Misc


## MON – Monitoring and Maintenance
- [MON-010 Set Up Uptime Monitoring](./MON/MON-010_Setup-Uptime-Monitoring.md)  
- [MON-020 Configure Docker Log Rotation](./MON/MON-020_Log-Rotation.md)  
- [MON-030 Check System Health Metrics](./MON/MON-030_System-Health-Checks.md)  

## SEC – Security Hardening
- [SEC-010 Restrict SSH to Key Based Login](./SEC/SEC-010_SSH-Key-Only-Login.md)  
- [SEC-020 Lock Down Firewall Defaults](./SEC/SEC-020_Firewall-Defaults.md)  
- [SEC-030 Enable Automatic Updates](./SEC/SEC-030_Auto-Updates.md)  
- [SEC-040 Protect n8n Credentials](./SEC/SEC-040_n8n-Credential-Protection.md)  

## TAIL - ailscale Document Links
- [TAIL-010 Tailscale Setup on GCP Ubuntu](./TAIL/TAIL-010_Tailscale_GCP_Ubuntu_Setup.md)
- [TAIL-020 Tailscale Troubleshooting](./TAIL/TAIL-020_Tailscale_Troubleshooting.md)


## UPG – Upgrades and Maintenance
- [UPG-010 Update Docker Images Safely](./UPG/UPG-010_Update-Docker-Images.md)  
- [UPG-020 Backup Workflow Data and Credentials](./UPG/UPG-020_Backup-Data.md)  
- [UPG-030 Restore from Backup](./UPG/UPG-030_Restore-From-Backup.md)  



## Legend / Key

| Prefix | Category | Description |
|:-------|:----------|:-------------|
| **GCP** | Google Cloud Platform | Cloud setup, APIs, credentials, VM, networking |
| **SYS** | System Configuration | SSH, users, packages, Tailscale |
| **DOCK** | Docker Environment | Docker Engine, Compose, validation |
| **MSC** | Misc.             | Vatious items withouta hone |
| **N8N** | n8n Setup & Integrations | Base install, connectors, notifications |
| **MON** | Monitoring | Uptime, logs, health checks |
| **SEC** | Security | SSH hardening, firewall, updates |
| **UPG** | Upgrades | Updates, backups, restores |
| **GIT** | backups  | GitHub related |
