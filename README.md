# Jenkins_pipeline

This project demonstrates how to set up a complete CI/CD pipeline using Jenkins. The following screenshots and explanations walk you through each critical phase, from job creation to successful deployment.

---

## 1. Creating a New Jenkins Item

![1](./img/1.%20new%20item.jpg)

Begin by creating a new item in Jenkins. Select "Pipeline" as the job type, which allows you to define complex build workflows as code.

---

## 2. Configuring the Pipeline Job

![1](./img/2.%20Pipeline%20job.jpg)  

![1](./img/3.%20configure.jpg)

Configure the job by specifying details such as the source code repository, build triggers, and pipeline script location. This setup ensures Jenkins knows where to fetch your code and how to execute the pipeline.

---

## 3. Writing the Pipeline Script

![1](./img/4a.%20script%20n%20syntax.jpg)

The pipeline script is the core of your automation. It defines the stages (e.g., build, test, deploy) and the steps within each stage. This script can be written directly in the Jenkins UI or stored in your repository.

---

## 4. Source Code Checkout

![1](./img/5.%20checkout.jpg)

The pipeline begins by checking out the latest code from your repository, ensuring every build uses the most recent version.

---

## 5. Generating and Running Build Scripts

![1](./img/6.%20generate%20script.jpg)  

![1](./img/7.%20generate.jpg)  

![1](./img/7A.%20CREATE%20FILE.jpg)

The pipeline can generate scripts dynamically or use predefined ones. These scripts automate tasks such as compiling code, running tests, or preparing deployment artifacts.

---

## 6. Docker Integration

![1](./img/8.%20DOCKER%20SCRIPT.jpg)

Docker scripts are used to build and manage containerized applications, ensuring your application runs in consistent environments across development, testing, and production.

---

## 7. Pipeline Execution and Monitoring

![1](./img/9.%20EXECUTION.jpg)  

![1](./img/10.%20ACTIVE.jpg)

Once configured, the pipeline is executed. Jenkins provides real-time feedback on build status and logs, helping you monitor progress and troubleshoot issues.

---

## 8. Deployment and Post-Build Steps

![1](./img/11.%20nginx%20script.jpg)  

![1](./img/12.%20commands.jpg)  

![1](./img/13.%20push.jpg)

After building, the pipeline can deploy the application (e.g., using Nginx), run additional commands, or push artifacts to a repository.

---

## 9. Output and Verification

![1](./img/14a.%20output.jpg)  

![1](./img/14.%20jenkins%20output.jpg)  

![1](./img/15.%20inbound%20rule.jpg)  

![1](./img/16.%20success.jpg)

The final screenshots show the output logs, Jenkins build results, network configuration (such as inbound rules for access), and confirmation of successful deployment.

---

## Conclusion

This Jenkins Pipeline project provides a robust, automated workflow for building, testing, and deploying applications. By leveraging scripts, Docker, and Jenkins' automation capabilities, you achieve a repeatable and reliable process. The detailed screenshots serve as a visual guide, making it easy to understand and replicate the setup. This approach accelerates development cycles, improves software quality, and ensures consistent delivery to production.



