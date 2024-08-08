#  Barkuni Corp
1. ./src is  RESTFull API written in Python/Flask
1. ./tf is Terraform module for init/provision EKS with VPC ( https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks )
2. ./Docker has multiple ways to write dockerfile for python apps (https://dev.to/isaackumi/dockerizing-a-flask-application-a-multi-stage-dockerfile-approach-389a)

Bonus: ./actions Continus Integration ( https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python)

Bonus: ./expose-kube-system Expose kube-system with Ingress Controllers

Ingresses: https://aws.amazon.com/blogs/containers/exposing-kubernetes-applications-part-3-nginx-ingress-controller/

Bonus: ALB with terraform https://github.com/terraform-aws-modules/terraform-aws-alb

Bonus: Route53 with Tf https://github.com/terraform-aws-modules/terraform-aws-route53/tree/master/examples/complete

4. ./Chart HelmChart could be 
   5. automated with Helmify ( https://github.com/thedataincubator/flask-chart ) 
   6. see all templates: https://github.com/arttor/helmify/tree/main/examples/app/templates
   7. see operators: https://github.com/arttor/helmify/tree/main/examples/operator/templates
   6. using best practises    https://github.com/davidh83110/flask-k8s-helm/tree/master
7. API Testing https://www.code-intelligence.com/rest-api-testing
8. ./boto3 ( ec2 + vpc full classes ) 


 
