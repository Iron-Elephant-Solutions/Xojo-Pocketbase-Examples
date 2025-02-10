# Xojo-Pocketbase-Examples
 A collection of example projects demonstrating how to integrate PocketBase with Xojo.

# Xojo-Pocketbase-Examples

This repository contains example projects demonstrating how to integrate [PocketBase](https://pocketbase.io) with Xojo. PocketBase is a lightweight, self-hosted backend that provides authentication, data storage, and real-time updates.

## Examples Included:
- **User Authentication**: How to log in and retrieve user data.
- **CRUD Operations**: Create, read, update, and delete records.

## Getting Started

To get started, I have simplified some steps below. If you get stuck or want more in depth instructions take a look at the documentation here: https://pocketbase.io/docs/
    - Download PocketBase: Visit https://pocketbase.io and download the latest release for your operating system.
    - Extract the files to your project directory.
    - Start the PocketBase server by navigating to the extracted folder in the command prompt/terminal.
    - Run the command: ./pocketbase serve to start the server.
    - Access the Admin Panel: Open http://127.0.0.1:8090/_/ in a web browser and set up an admin account.
    - Import the pb_schema.json found in the example apps folder into pocketbase. Click on the settings tab and select import. Followed by clicking the select "Load from JSON file".
    - Make sure Merge with existing collections is selected.
    - Finally run one of the example apps.
