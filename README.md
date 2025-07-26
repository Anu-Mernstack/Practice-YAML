# Practice-YAML
Why YAML is Important for Developers:
1. Infrastructure as Code (IaC)
Tools like Terraform, CloudFormation, and Pulumi use YAML (or JSON) to define infrastructure.

2. CI/CD Pipelines
Jenkins, GitHub Actions, GitLab CI, Azure Pipelines, and CircleCI use YAML to define workflows.
Example: .github/workflows/deploy.yml

3. Kubernetes Configuration
YAML is the standard for writing Kubernetes manifests (pods, deployments, services, etc.).

4. Configuration Files
Many tools and frameworks use YAML for settings:
docker-compose.yml
application.yml in Spring Boot
ansible-playbook.yml
helm charts

5. Readable and Easy to Maintain
YAML is human-readable, making it ideal for configuration over more verbose alternatives like XML or JSON.

What You Should Learn in YAML:
Concept                      	Description
Indentation	                  YAML uses spaces, not tabs. Consistent indentation is critical.
Key-value pairs	              Basic structure like key: value
Lists	                        Defined using - item syntax
Nested Structures	            Define nested dictionaries and lists
Comments	                    Use # for comments
Anchors & Aliases	            Reuse parts of YAML using & and *
Environment variables	        Used in CI/CD for secrets/configs
