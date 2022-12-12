## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### Proven Steps

  1. Job failed because of compile errors. 
  ![SCREENSHOT01](https://user-images.githubusercontent.com/102738849/207097142-e0f653e0-1019-4877-ac12-abd65d54847b.png)
 
  2. Job failed because of unit tests. 
   ![SCREENSHOT02-Backend](https://user-images.githubusercontent.com/102738849/207097286-1ec9a516-d296-471c-b2aa-4f0cc0372407.png)

  3. Job that failed because of vulnerable packages.
  ![SCREENSHOT03- scan backend](https://user-images.githubusercontent.com/102738849/207097513-15d378e3-6806-4113-becb-e4f209fd5be9.png)

  4. An alert from one of your failed builds. 
  ![SCREENSHOT04](https://user-images.githubusercontent.com/102738849/207097632-4136ca34-ce6d-41bc-9731-3c2626ee151b.png)

  5. Appropriate job failure for infrastructure creation. 
 ![SCREENSHOT05](https://user-images.githubusercontent.com/102738849/207098226-fc9204dd-02f7-43bb-911c-f74ef52e58f1.png)

  6. Appropriate job failure for the smoke test job. 
 ![SCREENSHOT06](https://user-images.githubusercontent.com/102738849/207099566-0ac64da2-7e8b-4608-975a-8c20e95d802a.png)

  7. Successful rollback after a failed smoke test.
 ![SCREENSHOT07](https://user-images.githubusercontent.com/102738849/207100227-3b9f5167-08ce-49c3-964c-edd9b124bcb1.png)

 
  8. Successful promotion job.
 ![SCREENSHOT08](https://user-images.githubusercontent.com/102738849/207100324-46ac3049-3236-410a-8442-aeebfb543485.png)

  9. Successful cleanup job.
![SCREENSHOT09](https://user-images.githubusercontent.com/102738849/207100450-11ef2744-c8a7-4dfa-be19-7b9f2af74bc2.png)

  10. Only deploy on pushed to `master` branch.
  ![SCREENSHOT10](https://user-images.githubusercontent.com/102738849/207100562-dc2e5dd2-b60a-414f-b14d-1303976e8e14.png)

  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage.
![SCREENSHOT11-available disk space](https://user-images.githubusercontent.com/102738849/207100826-689f0303-5a69-48a2-a3dd-c4daa9a71b53.png)
![SCREENSHOT11-available memory](https://user-images.githubusercontent.com/102738849/207100923-30e7f89d-c1c9-468e-b555-dc62b306b930.png)
![SCREENSHOT11-CPU Usage](https://user-images.githubusercontent.com/102738849/207101002-e1772d59-67e7-4f1b-8e5c-8288c697f8c4.png)

  12. Provide a screenshot of an alert that was sent by Prometheus.
 ![SCREENSHOT12](https://user-images.githubusercontent.com/102738849/207101080-b20856a3-4cb3-4040-a745-732c74f3f7af.png)
 
  13. all pipeline finished successfully
  ![Screenshot (206)](https://user-images.githubusercontent.com/102738849/207103155-bf9ae314-0a0f-4547-a051-c9d7cb3ca0bb.png)






