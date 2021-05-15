pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                echo 'Setup stage'
			}
        }
		stage('Compile'){
			steps{
				echo 'Compile stage'
				echo "Compile %date%:%time%"
			}
		}
		stage('validate'){
			steps{
				echo 'validate done'
			}
		}
    }
}
