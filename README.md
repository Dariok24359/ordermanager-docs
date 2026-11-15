# A.Mail - Documentation

## Overview
A.Mail is a private, desktop-based customer service application built in Python (Tkinter). It connects directly to the Allegro REST API via `device_code` authorization to fetch customer messages, discussions, and post-purchase disputes for internal seller account management.

## Features
- Secure OAuth2 authentication (`device_code` flow).
- Retrieval and management of Allegro messages, discussions, and disputes.
- Local SQLite data synchronization and automated response handling.

## Scope of API Access
The application strictly requests the following scopes for personal seller account operations:
- `allegro:api:messaging`
- `allegro:api:disputes`
- `allegro:api:orders:read`
