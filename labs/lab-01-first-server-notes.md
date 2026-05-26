# DevOps Foundation Notes

## Video 2 - DevOps Tools

### What I understood

DevOps is about moving an application from an idea to production in a faster, safer and more automated way.

The basic flow is:

Idea → Code → Build → Test → Deploy → Monitor → Improve

DevOps is not just one tool. It is a combination of people, processes and tools that help teams deliver software consistently.

### Tools mentioned

- Git: tracks code changes and allows multiple developers to work together.
- GitHub: online platform where Git repositories are stored and shared.
- Jenkins / GitHub Actions / GitLab CI/CD: automate build, test and deployment steps.
- Docker: packages the application with its dependencies so it can run the same way on different systems.
- Kubernetes: manages containers, keeps them running, restarts them if they fail, and can scale them.
- Terraform: creates infrastructure using code, such as servers, networks and storage.
- Ansible: configures servers after they are created, such as installing software and applying settings.
- Prometheus: collects monitoring metrics from servers and applications.
- Grafana: displays monitoring data in dashboards and graphs.

### Important differences

Git is the tool used for version control.  
GitHub is the online platform where Git repositories are hosted.

Docker runs containers.  
Kubernetes manages many containers across servers.

Terraform creates infrastructure.  
Ansible configures infrastructure after it exists.

Prometheus collects metrics.  
Grafana visualizes metrics.

### My real-life connection

This connects to my QUESTPAUSE experience because I already manage real servers, bots, logs, backups, monitoring and alerts.

My goal is to connect this real operational experience with professional DevOps tools like Linux, Git, Docker, CI/CD, Terraform, Ansible, Kubernetes and monitoring.

### Questions I still have

- When should I use Docker only, and when should I use Kubernetes?
- When should I use Terraform instead of Ansible?
- How does a real CI/CD pipeline look in a company?
- How can I connect monitoring tools to my own server projects?