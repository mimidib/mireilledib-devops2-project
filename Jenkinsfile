pipeline {
	agent any
	stages {
	    stage("Mireille Dib - Build Docker Image"){
	        steps{   
		        sh "echo executing the stage Build Docker Image"
            sh "docker image build -t mireilledib:devops2 ."
		}
	    }
	    stage("Mireille Dib - Login to Dockerhub"){
		steps {
		    sh "echo executing the stage Login to Dockerhub"
        sh "docker login"
        sh "${username}"
        sh "${password}"
		}
	    }
      stage("Mireille Dib - Push Image to Dockerhub"){
		steps {
		    sh "echo executing the stage Push Image to Dockerhub"
        sh "docker image tag mireilledib:devops2 ${username}/mireilledib:devops2"
        sh "docker image push ${username}/mireilledib:devops2"
		}
	    }
	}
}
