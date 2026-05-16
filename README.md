Self-hosted homelab running on a repurposed PC. The main goal is to learn and practice DevOps, networking, and infrastructure concepts in a real environment — not just theory.

Stack: Proxmox VE · Cloudflare Tunnel · Cloudflare Zero Trust · LXC containers

Currently running:
- Proxmox hypervisor exposed securely via Cloudflare Tunnel (no open ports)
- Cloudflare Zero Trust Access as an auth layer (email OTP)
- cloudflared in config-file mode with noTLSVerify for self-signed cert handling

In progress:
- Self-hosted LLM (local inference, exposed via tunnel)
- Local DNS server (internal name resolution)
- Let's Encrypt cert via Proxmox ACME + Cloudflare DNS challenge

Domain: homelabpaulobarros.com
