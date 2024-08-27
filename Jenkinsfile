pipeline {
    agent any

    stages {
        stage('Greetings') {
            steps {
                echo 'Hello World'
            }
        }
		
		stage ('Check_File_Exists') {
		    steps {
		        script{
			        if (fileExists('C:/Users/ADMIN/guvi-practice/mydirectory/demo1.txt')) {
				echo "File exists"
			        }
			else {
				echo "No such file exists"
			}
				    
			}
	}
		    }
}
}