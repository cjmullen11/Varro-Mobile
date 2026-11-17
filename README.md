# Varro Mobile

**Status:** Planned  
**Technologies:** Mobile Development · Bluetooth · Audio Streaming · HTTP APIs

## Overview

Varro Mobile is a phone application for interacting with the Varro assistant and connecting the portable Varro Companion device. I am designing it to provide a mobile chat interface while relaying Companion audio and controls to Varro's network services.

The **Varro** name honors Marcus Terentius Varro, a Roman scholar associated with wide-ranging knowledge.

## Key Design Choices

- **Dual purpose:** Provide a direct mobile client and a network bridge for the battery-powered Companion.
- **Bluetooth device link:** Exchange audio and control messages with the Companion; the final transport and mobile framework remain to be selected.
- **Server-side intelligence:** Send speech and requests to Varro services instead of running the primary assistant on the phone.
- **Shared state:** Let the orchestrator own conversations and memory across mobile, web, and voice interfaces.

## Roadmap

- [ ] Select the mobile platform and define app/backend interfaces.
- [ ] Prototype pairing and Bluetooth audio/control transport.
- [ ] Integrate speech sessions with the Varro Voice Server.
- [ ] Add basic chat, session controls, and interaction feedback.
- [ ] Test voice interactions over Wi-Fi and cellular connections.

## Usage

### Requirements

### Setup

### Configuration

### Operation
