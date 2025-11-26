# Scope of the solution

Scope of the solution
<div style="text-align: justify;">
The Hybrid Cloud Service Marketplace provides a unified platform to
manage all cloud resources. It can be used by the customers to
provision, orchestrate and automate infrastructure. It empowers
developers and DevOps teams to provision standardized resources and
enables governance through integrated approval workflows and
cross-platform policies. The project uses the Backstage.io (based on
ReactJS and NodeJS) and Django (based on Python) frameworks with a
managed Postgres Database. This web application is developed and built
into Docker Container platform images using CI/CD pipeline of GitHub and
pushed into AWS’s ECR. HCSM solution will be deployed in Kyndryl managed
account under AWS Control Tower landing zone and offered to client as a
SaaS model. AWS CloudFormation templates are used to automatically
create the required AWS resources like ECS, RDS Postgres, etc., and
deploy the docker container images from ECR, onto ECS. The end point of
the application is exposed to internet via AWS WAF and CloudFront
layers. Users will be able to access the application over internet, via
web browser. Solution goes thru standard dev, stage and production
environment on the same AWS account of client.
</div>
