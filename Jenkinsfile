pipeline {
	agent any 
			
			stages{
				 
				 stage('Terraform int') {
				 	steps{
				 			sh 'terraform init '
				 			}
				 		}
				 stage('Terraform validate') {
				 	steps{
				 			sh 'terraform validate'
				 			}
				 		}
				 stage('Terraform Plan') {
				 	steps{
				 			sh 'terraform plan'
				 			}
				 		}
				 stage ('Terraform Apply') {
				 	steps{
				 			sh 'terraform apply -auto-approve '
				 			}
				 		}
				 	}
				 }
