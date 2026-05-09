# ROS2 Docker Publisher-Subscriber

Multi-container ROS2 system demonstrating publisher-subscriber pattern using Docker.

## Quick Start

**Prerequisites:** Docker Desktop installed and running

**Run the system:**
```bash
docker-compose up --build
```

You'll see the publisher sending sensor data and the subscriber receiving it in real-time.

**Stop:** Press Ctrl+C

## Architecture

- **Publisher container:** Publishes sensor readings every second
- **Subscriber container:** Listens and logs received data
- **ROS2 communication:** Both containers on shared network with ROS_DOMAIN_ID=42

---

## Author
Nassib El Saghir — [LinkedIn](https://linkedin.com/in/nassib-el-saghir) — [GitHub](https://github.com/nassib-es)