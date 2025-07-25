🕒 Uptime Kuma - Self-hosted Uptime Monitoring

Uptime Kuma monitors the uptime status of services, servers, and endpoints.

🔧 Docker Compose Example

  uptime-kuma:
    image: louislam/uptime-kuma:latest
    container_name: uptime-kuma
    restart: always
    volumes:
      - ./uptime-kuma:/app/data
    ports:
      - "3001:3001"

🧠 Use Cases

Monitor your Minecraft server (TCP port 25565)

Monitor public or private services

Get real-time alerts on service failures

🌐 Access

http://<your-pi-ip>:3001
