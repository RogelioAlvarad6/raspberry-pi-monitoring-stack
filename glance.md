📈 Glances - Real-time System Resource Monitoring

Glances is a cross-platform system monitoring tool written in Python. It provides real-time stats for:

--> CPU

--> Memory

--> Disk

--> Network

--> Sensors

🔧 Installation via Docker

  glances:
    image: nicolargo/glances:latest
    container_name: glances
    restart: always
    network_mode: host
    pid: host
    volumes:
      - /var/run/docker.sock:/var/run/docker.sock:ro
    environment:
      - GLANCES_OPT=-w

🌐 For Access

Visit:

http://<your-pi-ip>:61208

