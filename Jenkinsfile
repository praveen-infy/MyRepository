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
				fileExists 'Multi_Config_Project'
			}
		}
		stage('validate'){
			steps{
				echo 'validate done'
			}
		}
    }
}
