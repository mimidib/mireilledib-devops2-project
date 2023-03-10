pipeline {
	agent any
	stages {
	    stage("Mireille Dib - Build Docker Image"){
	        steps{   
		    sh "echo executing the stage Build Docker Image"
		    sh "docker image build"
		}
	    }
	    stage("Mireille Dib - Login to Dockerhub"){
		steps {
		    sh "echo executing the stage Login to Dockerhub"
		}
	    }
      stage("Mireille Dib - Push Image to Dockerhub"){
		steps {
		    sh "echo executing the stage Push Image to Dockerhub"
		}
	    }
	}
}
