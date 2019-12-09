pipeline {
    agent any
    stages {
        stage('Upload to AWS') {
            steps {
            			withAWS(region:'us-west-2',credentials:'aws-static') {
                			s3Upload(bucket:'udacity-devops-project3', file:'index.html', path:'');
            			}
             }
         }
     }
 }
