node{
    stage 'Checkout Terraform Project'
        git 'https://gitlab.com/vishnukiranreddy4/terraformrepo.git'
    stage 'INIT'
        bat 'terraform init'
    stage 'SANITY CHECK'
        bat 'terraform validate'
    stage 'PLAN'
        bat 'terraform plan'
    stage 'FORMAT'
        bat 'terraform fmt'
    stage 'APPLY'
        bat 'terraform apply'
    
}
