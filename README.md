🐳 Docker + Docker Compose

Docker allows containerized applications to run easily across environments. Docker Compose helps define and run multi-container apps.

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


