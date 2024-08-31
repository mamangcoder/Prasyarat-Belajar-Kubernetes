# Beberapa hal yang perlu diketahui sebelum mempelajari K8s
## 1. Containerization (Docker)
### Apa yang Harus Dipelajari:
1. Docker Commands:
Master key commands ( docker run , docker ps , docker stop , etc.) for container
management.
2. Dockerfiles:
Understand Dockerfile structure.
Write Dockerfiles to define custom container images.
3. Docker Images:
Grasp the concept of Docker images.
Learn to build and customize images.
Things to know before learning K8s 2
4. Docker Containers:
Understand container lifecycle and benefits.
Manage networks, volumes, and environment variables.
5. Docker Compose:
Use Docker Compose for multi-container applications.
Configure services with docker-compose.yml .

## 2. Linux Commands 
### Apa yang Harus Dipelajari di Linux:
1. Basic Commands:
Master essential commands for file management and navigation.
2. File Permissions:
Understand how to set and modify file permissions.
3. Process Management:
Learn commands for monitoring and managing processes.
4. Networking Basics:
Familiarize yourself with commands for network troubleshooting.
5. Text Editors (e.g., Vim, Nano):
Acquire proficiency in terminal-based text editors for quick edits.
Things to know before learning K8s 3
6. System Information:
Explore commands for gathering insights into system resources.

## 3. Networking
Di Kubernetes, memahami Networking sangatlah penting. Tanpa mengetahui tentang hal-hal seperti
port, load balancers, dan firewall, Anda akan sulit menyiapkan aplikasi Kubernetes.

Jaringan adalah masalah besar di Kubernetes, yang perlu dipahami
bagaimana Deployment, Pod, dan Layanan berkomunikasi satu sama lain.
### Apa yang harus dipelajari:
- Gain foundational knowledge in networking.
- Understand IP addressing concepts, including IPv4 and IPv6.
- Familiarize yourself with routing principles and how data is directed between networks.
- Learn subnetting to efficiently allocate IP address ranges within a network.
- Grasp basic network protocols, such as TCP/IP and UDP, to comprehend data
communication principles.
- Recognize the integral role of networking in facilitating communication within Kubernetes
clusters.

## 4. Understanding Microservices
Microservices is architecture pattern followed by Kubernetes, where each service is deployed
as a container. So having understanding of Microservices work is really important.

For instance, if an E-commerce application follows the microservice architecture, it will
comprise the database service as a container, the frontend service in another container, and
the backend service in another container, all working together to make the E-commerce
application work flawlessly.

### What to learn?
- Microservices Basics:
Understand Microservices as an architectural pattern for breaking down applications
into small, independent services.
- Service Communication:
Learn how Microservices communicate, starting with an introduction to RESTful APIs.
- Independence and Autonomy:
Grasp the concept of each Microservice operating independently with its own database
and functionality.
- APIs:
Gain a basic understanding of how Microservices expose APIs
- Hands-On Projects:
Apply knowledge through hands-on projects or small applications, reinforcing
Microservices principles through practical experience.

## 5. Cloud Provider 
Kubernetes biasanya diterapkan di cloud.
Menerapkan Kubernetes di cloud menawarkan berbagai keuntungan, Pertama, platform cloud seperti
AWS, Azure, atau GCP menyediakan infrastruktur yang diperlukan untuk menghosting cluster Kubernetes,
termasuk mesin virtual, penyimpanan, dan layanan jaringan.

### What to learn?
- Cloud Fundamentals: On-demand provisioning, scalability, pay-as-you-go.
- Major Cloud Platforms: AWS, Azure, GCP. (Managed Kubernetes Cluster setup)
- Deployment Models: Public, private, hybrid clouds.
- Service Models: IaaS, PaaS, SaaS.
- Basic Networking: Virtual networks, subnets, security groups.
- IAM (Identity and Access Management): User roles, permissions.
- Storage Services: Object, block, file storage.
- Security Best Practices: Encryption, access controls, compliance.
- Cost Management: Monitoring, budgeting, optimization.
- Hands-On Practice: Experiment on a cloud platform for practical experience.

## YAML
YAML - Yet Another Markup Language or “YAML Ain’t Markup Language”
YAML is to create manifest files responsible to create kubernetes object in declarative way. So
having understanding of how to write in YAML is important!

### What to learn?
- Basic syntax, key-value pairs, lists.
- Data types: strings, numbers, booleans.
- Handling lists, arrays, dictionaries, and nested structures.
- Practical use in configuration files (e.g., Kubernetes).
- Validation tools, best practices, error handling

