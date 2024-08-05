# Git-Cloudtype(PaaS) CI/CD Test


- Automatically run a build when a pull-request is created
  - name: Checkout
  - name: setup jdk
  - name: Grant execute permission for gradlew
  - name: gradlew test
- Automatically deploy when a main branch is pushed
  - name: Checkout
  - name: Connect deploy key
  - name: Deploy
- Add a CI workflow(workflow-job-step) on Git
- Deploy to Cloudtype(PaaS)
- 
<img width="949" alt="cicd_cloudtype_img" src="https://github.com/user-attachments/assets/0640f6f2-5717-4374-8f20-d28a2ad64f9f">
