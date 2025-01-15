pipeline{
    agent any

    stages{
        stage("Fetch code"){
            steps{
                git branch: 'pipeline', url: "https://github.com/Augustine184/work.git" 
            }
        }

        stage("Try once"){
            steps
                {
                echo "Hellobro"
            }
        }
    }
}