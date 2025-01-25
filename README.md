siddharth
🚀 𝗕𝗹𝘂𝗲-𝗚𝗿𝗲𝗲𝗻 𝗖𝗜/𝗖𝗗 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁 𝘄𝗶𝘁𝗵 𝗜𝗻𝗳𝗿𝗮𝘀𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲 𝗔𝘂𝘁𝗼𝗺𝗮𝘁𝗶𝗼𝗻 𝗮𝗻𝗱 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁

I’m excited to share one of my recent projects: a Blue-Green CI/CD Deployment Pipeline integrated with 𝗜𝗻𝗳𝗿𝗮𝘀𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲 𝗔𝘂𝘁𝗼𝗺𝗮𝘁𝗶𝗼𝗻 and 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁 on 𝗔𝗺𝗮𝘇𝗼𝗻 𝗘𝗞𝗦!

This project combines 𝗧𝗲𝗿𝗿𝗮𝗳𝗼𝗿𝗺, 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀, and modern 𝗖𝗜/𝗖𝗗 practices to streamline deployments, ensure seamless environment switching, and enhance security.

🔗 𝗚𝗶𝘁𝗛𝘂𝗯 𝗥𝗲𝗽𝗼𝘀𝗶𝘁𝗼𝗿𝘆: https://lnkd.in/d2JXZsbW

🌐 𝗜𝗻𝗳𝗿𝗮𝘀𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁

Using 𝗧𝗲𝗿𝗿𝗮𝗳𝗼𝗿𝗺, I automated:
 • Creating a 𝗩𝗣𝗖 with subnets, internet gateways, and route tables.
 • Designing 𝘀𝗲𝗰𝘂𝗿𝗶𝘁𝘆 𝗴𝗿𝗼𝘂𝗽𝘀 for EKS clusters and worker nodes with IAM roles for permissions.
 • Deploying an 𝗔𝗺𝗮𝘇𝗼𝗻 𝗘𝗞𝗦 𝗰𝗹𝘂𝘀𝘁𝗲 with worker nodes to manage Kubernetes workloads.

This setup ensures fast, repeatable, and reliable infrastructure provisioning.

🔄 𝗣𝗶𝗽𝗲𝗹𝗶𝗻𝗲 𝗖𝗼𝗻𝗳𝗶𝗴𝘂𝗿𝗮𝘁𝗶𝗼𝗻

Built a robust CI/CD pipeline with:
 • 𝗠𝗮𝘃𝗲𝗻𝟯, 𝗗𝗼𝗰𝗸𝗲𝗿, 𝗧𝗿𝗶𝘃𝘆 and 𝗦𝗼𝗻𝗮𝗿𝗤𝘂𝗯𝗲 for complete lifecycle automation.
 • Environment variables like 𝗗𝗘𝗣𝗟𝗢𝗬_𝗘𝗡𝗩, 𝗗𝗢𝗖𝗞𝗘𝗥_𝗧𝗔𝗚, and 𝗪𝗜𝗧𝗖𝗛_𝗧𝗥𝗔𝗙𝗙𝗜𝗖 for flexible deployments.

🛠️ 𝗣𝗶𝗽𝗲𝗹𝗶𝗻𝗲 𝗦𝘁𝗮𝗴𝗲𝘀

The pipeline automates key steps:
 1. 𝗚𝗶𝘁 𝗖𝗵𝗲𝗰𝗸𝗼𝘂𝘁: Clones the GitHub repository.
 2. 𝗖𝗼𝗺𝗽𝗶𝗹𝗲: Builds the project using Maven.
 3. 𝗧𝗲𝘀𝘁𝘀: Executes unit tests.
 4. 𝗧𝗿𝗶𝘃𝘆 𝗙𝗦 𝗦𝗰𝗮𝗻: Detects vulnerabilities in the filesystem.
 5. 𝗦𝗼𝗻𝗮𝗿𝗤𝘂𝗯𝗲 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀: Ensures code quality through quality gates.
 6. 𝗕𝘂𝗶𝗹𝗱: Packages the application into a deployable artifact.
 7. 𝗣𝘂𝗯𝗹𝗶𝘀𝗵 𝗔𝗿𝘁𝗶𝗳𝗮𝗰𝘁𝘀 𝘁𝗼 𝗡𝗲𝘅𝘂𝘀: Manages artifact versions in Nexus.
 8. 𝗗𝗼𝗰𝗸𝗲𝗿 𝗕𝘂𝗶𝗹𝗱 & 𝗣𝘂𝘀𝗵: Builds and pushes images to Docker Hub.
 9. 𝗧𝗿𝗶𝘃𝘆 𝗜𝗺𝗮𝗴𝗲 𝗦𝗰𝗮𝗻: Scans Docker images for vulnerabilities.

🚀 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁 𝗦𝘁𝗮𝗴𝗲𝘀
 • 𝗠𝘆𝗦𝗤𝗟 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁: Configures and deploys MySQL on Kubernetes.
 • 𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁: Deploys backend and frontend services.
 • 𝗕𝗹𝘂𝗲-𝗚𝗿𝗲𝗲𝗻 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁: Dynamically switches between blue and green environments for zero-downtime rollouts.
 • 𝗧𝗿𝗮𝗳𝗳𝗶𝗰 𝗦𝘄𝗶𝘁𝗰𝗵𝗶𝗻𝗴: Redirects traffic seamlessly using Kubernetes service patches.
 • 𝗩𝗲𝗿𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻: Validates health and stability post-deployment.

A big thank you to Aditya Jaiswal and DevOps Shack—your tutorials simplified complex concepts and were invaluable to this project.

