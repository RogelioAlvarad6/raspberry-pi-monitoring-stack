🐳 Docker + Docker Compose

Docker allows containerized applications to run easily across environments. Docker Compose helps define and run multi-container apps. Essentially ..... Docker = App-in-a-box and let's say for an example, imagine you’re running an app like Minecraft, and instead of manually installing Java, configuring files, and dealing with versions. Docker gives you a magic box with Minecraft pre-installed, configured, and ready to go.
You just say:
**docker run minecraft-image**
and it runs.

Now Docker Compose is essentially a Multi-box project. Now imagine you want:

- A Minecraft server

- A monitoring dashboard

- A backup service

- Maybe a website too (hint at my next project and self hosted)

Then Docker Compose is like a blueprint for all your magic boxes.

🔧 Installation

Docker:

sudo apt update
sudo apt install -y docker.io
sudo systemctl enable --now docker
sudo usermod -aG docker $USER

Docker Compose:

sudo apt install -y docker-compose

📁 Recommended Project Structure

Create a folder (e.g., ~/docker/monitoring) and store the docker-compose.yml file there.

🚀 Usage

cd ~/docker/monitoring
docker-compose up -d

✅ Services

glances at http://<pi-ip>:61208

uptime-kuma at http://<pi-ip>:3001


