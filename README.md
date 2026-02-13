# Unraid Docker Templates

## What is this repository?
This repository contains a collection of custom XML templates for Unraid's Docker containers. These templates are designed to be fully compatible with the Unraid Community Applications (CA) plugin.

## Why did I create this?
Sometimes, new or beta software (like the TeamSpeak 6 Beta Server) is not yet available in the official Unraid Community Applications store. 
I created this repository to provide easy, "one-click" installation templates for the community. By sharing these XML files, I want to save other Unraid users the hassle of configuring ports, paths, and variables completely from scratch.

## How to use these templates
If you want to use these templates on your own Unraid server:
1. Copy the raw URL of the `.xml` file you need.
2. Place it inside your Unraid flash drive under `/boot/config/plugins/dockerMan/templates-user/`.
3. Go to your Unraid Docker tab, click "Add Container", and select the newly added template from the "Template" dropdown menu.

## Current Templates
* **TeamSpeak 6 Server (Beta):** A ready-to-use template for the official TS6 Docker image, including all necessary ports (Voice, File Transfer) and proper Appdata folder permissions.

---
*Feel free to use, modify, or suggest improvements!*
