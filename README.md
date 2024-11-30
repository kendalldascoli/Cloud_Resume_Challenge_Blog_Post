# Cloud Resume Challenge Blog Post
## What is the Cloud Resume Challenge?
The Cloud Resume Challenge is a hands-on project for people looking to bridge the gap between a cloud certification and a cloud job where you gain hands-on skills in building and deploying a fully cloud-hosted resume. To do so you code your resume in HTML, CSS, Javascript, and Python, host your resume on the AWS cloud using cloud storage, HTTPS, a CDN, DNS, and a NoSQL database, and deploy the cloud resources to host your resume with infrastructure as code, source control, and CI/CD. This challenge pushes you to combine technical skills in a way that mimics those of a real cloud engineer. For me, this project was an opportunity to test my skills, deepen my understanding of cloud engineering, and gain confidence in tackling complex technical tasks.
## Building the Frontend
One of the first tasks was creating a visually appealing, static resume hosted on the cloud. I used HTML, CSS, and JavaScript to code my resume. I then deployed it on a static website using AWS S3 for storage and hosting it through CloudFront, a CDN that delivers cached content to my webpage’s visitors with low latency and high transfer speeds. I ensured my domain name was professional and secure, managing the DNS settings through Route 53. 
This first group of steps increased my excitement for this challenge as it felt like a rewarding milestone that built my confidence in tackling more complex backend tasks. I was able to successfully troubleshoot to ensure that both my root domain and subdomain were routed through CloudFront and not directly to my S3 bucket which deepened my understanding of the importance of caching and domain security. 
## Building the Backend
To bring my resume to life with interactive functionality, such as a visitor counter, I connected the frontend to a serverless backend. Enabling my visitor counter feature tested my cloud expertise, where I worked with AWS Lambda, DynamoDB, and API Gateway. I set up my DynamoDB database, a NoSQL database, to store my visitor count due to its scalability, affordability, and durability. Next, I configured the AWS Lambda function written in Python so the API, made with API Gateway, could recall the visitor counter data in DynamoDB for the updated count. Once Lambda, DynamoDB, and my API were configured, I was ready to fully connect my frontend and backend by implementing my JavaScript saved in my S3 bucket so the count visually appeared on my website. After implementing JavaScript in the S3 bucket to connect the frontend and backend, I felt accomplished in building a fully functional, cloud-native application.
## Infrastructure and Automation
The final requirements were building the infrastructure using Terraform, automating the frontend/backend, and implementing a CI/CD pipeline. Updates to the infrastructure were efficiently managed and deployed through GitHub's version control system. By committing changes to the repository, automated workflows using GitHub Actions were triggered to deploy updates directly to the S3 bucket. This automated process streamlined deployments, ensuring that all upgrades were consistent and required minimal manual effort, ultimately enhancing efficiency and reliability in infrastructure management.
## Key Learnings and Takeaways
Throughout this challenge, I was able to test my understanding of cloud architecture. I developed skills in serverless architecture, API design, IaC, and DNS. Beyond growing in my technical skills, the Cloud Resume Challenge has taught me valuable problem-solving skills, and how to be resourceful in overcoming challenges. I learned the importance of breaking down complex issues into smaller, more manageable tasks. I utilized AI, Google search, and the various Cloud Resume Challenge communities online that gave countless solutions and troubleshooting steps. The outcome of this experience has been extremely rewarding, proving to myself that I can accomplish things that are difficult and that I may not know much about in the beginning. 
I am looking forward to taking the cloud infrastructure skills that I have been developing over the past few months to my future career and continuing to grow and learn. I am also studying to take the AWS Certified Cloud Practitioner Certification test to become a Certified Cloud Practitioner and look forward to applying it to my future coursework and career. I would recommend the Cloud Resume Challenge to anyone looking to dive deeper into cloud practices and test their abilities to critically think and overcome roadblocks.


