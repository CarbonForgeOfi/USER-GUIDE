# 🚀 CarbonForge VPS Management – Complete User Guide

Welcome to **CarbonForge**! This is your complete guide to deploying and managing VPS containers on the CarbonForge Discord server.

**Important:** This bot is exclusive to the CarbonForge Discord server and cannot be added to other servers.

---

## 🔗 CarbonForge Links

* **GitHub** — [https://github.com/CarbonForgeOfi](https://github.com/CarbonForgeOfi)
* **TikTok** — [https://www.tiktok.com/@carbonforgeofi](https://www.tiktok.com/@carbonforgeofi)
* **Discord** — [https://discord.gg/MSUAmVu7d9](https://discord.gg/MSUAmVu7d9)

---

## 📋 Table of Contents

* [Getting Started](#getting-started)
* [Deploying Your First VPS](#deploying-your-first-vps)
* [All Commands Explained](#all-commands-explained)

  * [Getting Started Commands](#getting-started-commands)
  * [Container Management](#container-management)
  * [System Monitoring](#system-monitoring)
  * [Network Tools](#network-tools)
  * [Development Tools](#development-tools)
  * [File Management](#file-management)
  * [Maintenance Commands](#maintenance-commands)
* [Daily VPS Management](#daily-vps-management)
* [Troubleshooting](#troubleshooting)
* [Support and Credits](#support-and-credits)

---

## Getting Started

### What is CarbonForge?

CarbonForge is a VPS hosting service managed through Discord. You can deploy, manage, and monitor your virtual private servers directly from the CarbonForge Discord server using simple commands.

**What you can do:**

* Deploy VPS instances
* Start, stop, and reboot containers
* Monitor CPU, RAM, and disk usage
* Manage billing and invoices
* Upload and share files
* Use built-in network tools
* Develop with Python, Node.js, Docker, and Git pre-installed

### How to Use This Guide

1. Join the CarbonForge Discord server
2. Read the deployment section to create your first VPS
3. Learn the commands to manage your VPS
4. Use the troubleshooting section if you encounter issues

---

## Deploying Your First VPS

### Step 1: Join the CarbonForge Discord Server

All commands must be used inside the official CarbonForge Discord server.

### Step 2: Check Available Plans and Pricing

Use the following Discord command:

/price

Select a plan and the number of days to view pricing details.

### Step 3: Deploy Your VPS

Use:

/deploy

Provide a container name, select a plan, and choose the duration.

### Step 4: Receive Invoice

After deployment, you will receive an invoice via Discord direct message containing:

* Invoice ID
* Total amount
* Payment instructions

### Step 5: Make Payment

Include the Invoice ID in your payment note so it can be verified.

### Step 6: Wait for Deployment

Once payment is confirmed, your VPS will be deployed automatically.

### Step 7: Access Your VPS

Use:

/dashboard

This shows your IP address, SSH port, credentials, and usage stats.

---

## All Commands Explained

### Getting Started Commands

#### /help

Displays all available commands.

#### /dashboard

Shows container status, SSH access details, and resource usage.

#### /whoami

Displays your Discord account role and owned containers.

---

### Container Management

#### /power

Start, stop, or reboot your container.

#### /passwd

Change the SSH root password.

#### /pause

Pause your container to save time (paid plans only).

#### /resume

Resume a paused container.

#### /extend

Extend your container subscription.

#### /changeplan

Upgrade or downgrade your plan.

**Upgrade discount (important):**

- If you **upgrade within the first 3 days** after your VPS is activated **and** you have **at least 7 days remaining**, you **don’t pay the full new plan price**.
- Instead, you only pay the **difference** between plans for your remaining time:
  - \((new_plan_price - current_plan_price) × days_remaining\)
- **Special rule:** If you are on **ADVANCED**, you can upgrade to a higher plan **anytime** and it will still be **pro‑rated** (difference only).

If you try to upgrade with **less than 7 days remaining**, you’ll be asked to use `/extend` first.

#### /price

Calculate pricing for a selected plan.

---

### System Monitoring

#### /stats

View CPU, RAM, disk, and uptime information.

#### /ports

Show IP address and SSH connection details.

#### /disk

View disk usage breakdown.

#### /processes

List running processes by resource usage.

#### /logs

View recent system logs.

#### /memory

Detailed memory usage.

#### /cpu_info

Detailed CPU information.

#### /storage

View storage devices and partitions.

#### /services

View running and stopped services.

---

### Network Tools

#### /network

Test network connectivity.

#### /speedtest

Run a network speed test.

#### /ip

View IP and DNS configuration.

#### /traceroute

Trace network route to a host.

#### /dns

Query DNS records.

#### /netstat

View active network connections.

#### /latency

Test latency to common servers.

---

### Development Tools

#### /python

Check Python version and packages.

#### /node

Check Node.js and npm versions.

#### /docker

View Docker status and containers.

#### /git

Check Git configuration.

#### /benchmark

Run a CPU benchmark.

---

### File Management

#### /share

Upload and share files up to 20GB.

#### /library

Browse shared community files.

#### /find_large

Locate large files using disk space.

---

### Maintenance Commands

#### /update

Update system packages.

#### /clean

Clean temporary files and free disk space.

---

## Daily VPS Management

Use `/dashboard` daily to monitor status, `/stats` to track usage, and `/update` regularly to keep your system secure.

---

## Troubleshooting

### Container Will Not Start

* Check status with `/dashboard`
* Start container with `/power`
* Review logs with `/logs`

### Cannot Connect via SSH

* Verify IP and port with `/ports`
* Ensure container is running
* Test network with `/network`

### High Resource Usage

* Use `/stats` and `/processes`
* Remove large files with `/find_large`
* Clean system with `/clean`

### Payment Issues

* Ensure Invoice ID was included
* Contact staff if payment is not confirmed

---

## Support and Credits

### Getting Support

* Use `/help` in Discord
* Ask for help in the CarbonForge Discord server
* Contact moderators or admins if needed

### Credits

CarbonForge Bot
Developer: Techoraye

---

Last Updated: December 2025
Version: CarbonForge v1.0
Server: CarbonForge Discord Server Only
