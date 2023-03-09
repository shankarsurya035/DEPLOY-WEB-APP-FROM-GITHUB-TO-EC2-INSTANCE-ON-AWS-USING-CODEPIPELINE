# DEPLOY-WEB-APP-FROM-GITHUB-TO-EC2-INSTANCE-ON-AWS-USING-CODEPIPELINE <br>

Building Websites and then Copying the code manually to the server via ftp is now a thing of the past. Having an automated system deploying the merged developer code in repo not only saves you time but also ensures that no changes are missed on the production deployent. Deployments have come a long way in the 10 years and the general goal today is to automate code deployments as much as possible. Let’s explore how we can deploy code from GitHub to EC2 using CodePipeline.

Explanation about Tools AWS CodePipeline – A continuous delivery service you can use to model, visualize, and automate the steps required to release your software. You can quickly model and configure the different stages of a software release process. CodePipeline automates the steps required to release your software changes continuously.
<br>
![image](https://user-images.githubusercontent.com/82276019/184545922-a3381d34-15cd-4131-98d2-76059cd4f827.png)
<br>

![cicd-github-to-EC2_page-0001](https://user-images.githubusercontent.com/82276019/224101280-618fe100-23d9-401e-843d-ebcd93463e0b.jpg)
![cicd-github-to-EC2_page-0002](https://user-images.githubusercontent.com/82276019/224101291-554bb76f-825c-47aa-80d8-5fc8a7da2c93.jpg)
![cicd-github-to-EC2_page-0003](https://user-images.githubusercontent.com/82276019/224101342-8908b48b-812a-4df7-9c51-f991b0215cb7.jpg)
![cicd-github-to-EC2_page-0004](https://user-images.githubusercontent.com/82276019/224101403-c865724e-f314-4195-a88d-f3e2babaa8e7.jpg)
![cicd-github-to-EC2_page-0005](https://user-images.githubusercontent.com/82276019/224101439-fb383713-c10d-4ba9-bd50-d14463a19215.jpg)
![cicd-github-to-EC2_page-0006](https://user-images.githubusercontent.com/82276019/224101554-bf7716b8-3b9d-415e-aa05-34185971520c.jpg)
![cicd-github-to-EC2_page-0007](https://user-images.githubusercontent.com/82276019/224101569-964252cd-b1bf-4e0b-8a49-d4d475238bc4.jpg)
![cicd-github-to-EC2_page-0008](https://user-images.githubusercontent.com/82276019/224101597-749b9dbb-91f9-4881-a48d-719d5b694e90.jpg)
![cicd-github-to-EC2_page-0009](https://user-images.githubusercontent.com/82276019/224101651-a404317d-f88b-416a-b3be-1f8f34df5edb.jpg)
![cicd-github-to-EC2_page-0010](https://user-images.githubusercontent.com/82276019/224101682-ff0e9b47-34cf-4cd2-99a8-2676c6964318.jpg)
![cicd-github-to-EC2_page-0011](https://user-images.githubusercontent.com/82276019/224101709-e7ebdcab-9d1a-4376-a02a-593fd806534f.jpg)
![cicd-github-to-EC2_page-0012](https://user-images.githubusercontent.com/82276019/224101786-523123db-ca7f-4a2e-9c78-fd65edaded65.jpg)
![cicd-github-to-EC2_page-0013](https://user-images.githubusercontent.com/82276019/224101802-ec4228a8-803a-4438-a941-e6ae1f61d042.jpg)
![cicd-github-to-EC2_page-0014](https://user-images.githubusercontent.com/82276019/224101809-d6c645ed-0f05-4500-a362-6e83cd208b23.jpg)
![cicd-github-to-EC2_page-0015](https://user-images.githubusercontent.com/82276019/224101920-86cf6154-bcc3-4fe2-8615-982ca0df3597.jpg)
![cicd-github-to-EC2_page-0016](https://user-images.githubusercontent.com/82276019/224102180-8605096e-56d7-49e2-836f-c872aacf0da5.jpg)
![cicd-github-to-EC2_page-0017](https://user-images.githubusercontent.com/82276019/224102190-f5f85411-c9a1-4195-b791-3f5705434b94.jpg)
![cicd-github-to-EC2_page-0018](https://user-images.githubusercontent.com/82276019/224102232-e7496ab4-751d-41d0-92b0-12993c035016.jpg)
![cicd-github-to-EC2_page-0019](https://user-images.githubusercontent.com/82276019/224102384-0af47737-0164-430e-ad16-39899d170e5d.jpg)
![cicd-github-to-EC2_page-0020](https://user-images.githubusercontent.com/82276019/224102403-22d5531b-2476-4042-82a3-b98be75c7f2c.jpg)
![cicd-github-to-EC2_page-0021](https://user-images.githubusercontent.com/82276019/224102484-98534ce2-5548-4894-b237-50f04bfca5d2.jpg)
![cicd-github-to-EC2_page-0022](https://user-images.githubusercontent.com/82276019/224102509-4c39ccba-7e69-430d-8259-b85925b22549.jpg)
![cicd-github-to-EC2_page-0023](https://user-images.githubusercontent.com/82276019/224102608-01f35624-eecf-4987-8cb1-b3669017c68d.jpg)




