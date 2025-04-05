# **Last Oasis Egg for Pterodactyl Panel**

This repository contains an **Egg** for installing and managing **Last Oasis** servers on **Pterodactyl Panel**. It enables you to easily configure and manage dedicated game servers through the web panel, using Docker containers for efficient server handling.

## **Game Description**
Last Oasis is a Nomadic Survival MMO set in a post-apocalyptic world where the Earth has stopped rotating. Survivors must outrun the scorching Sun while navigating vast, open-world landscapes. Players traverse the world using wooden, wind-powered walking machines known as "Walkers," which can be customized for combat, transportation, harvesting, and more.

## **Features**
- Quick installation and configuration of **Last Oasis** servers.
- Compatible with both dedicated servers and VPS setups.
- Customizable player slots, query ports, and server names.
- Support for both **CustomerKey** and **ProviderKey** for server setup.
- Auto-update functionality for the server.

## **Requirements**
- **Pterodactyl Panel**.
- **Docker**.
- **Ubuntu 20.04+** (or compatible Linux OS).

## **Installation & Setup**
1. Upload the `egg-last-oasis-s6.json` egg file to your **Pterodactyl Panel**.
2. Configure the environment variables:
   - **SRCDS_APPID** (default: `920720`).
   - **Server Name** (default: `YOUR NAME SERVER`).
   - **Query Port** (default: auto-generated).
   - **Server Slots** (default: `100`).
   - **Customer Key** and **Provider Key** (required from the Last Oasis site).
3. Start your server from the **Pterodactyl Panel**.

## **Credits**
- Docker image provided by [ParkervCP](https://github.com/parkervcp/).
- Server setup based on [Last Oasis server setup documentation](https://myrealm.lastoasis.gg/).
