# Pulsar

Real-time IoT monitoring platform: a Flutter mobile app and a FastAPI backend connected over MQTT.

> Status: in development

## Features (planned)
- Live sensor dashboard (temperature, humidity and more)
- Threshold alerts with push notifications
- Historical data charts
- Remote device control
- Device simulator for testing without hardware

## Tech stack
- **Mobile:** Flutter
- **Backend:** FastAPI, PostgreSQL, WebSocket
- **Messaging:** MQTT
- **Tooling:** Docker Compose, GitHub Actions

## Architecture
Devices (or the simulator) publish readings over MQTT. The backend stores them and streams them live to the app over WebSocket.

## Roadmap
- [ ] Backend setup and authentication
- [ ] Device simulator
- [ ] MQTT ingestion and storage
- [ ] Real-time and history APIs
- [ ] Flutter app: dashboard and charts
- [ ] Alerts and device control
- [ ] Tests, CI and screenshots

## Author
Mustafa
