pipeline {
    agent {
        label{
            label "slave2"
            customWorkspace "/mnt/private"
        }
    }
    stages{
        stage("cloning private repo"){
            steps{
                sh "rm -rf *"
                sh "git clone https://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@github.com/snehaos20/repo3.git"
                echo "cloning"
                sh "chmod -R 777 /mnt/private"
            }
        }
        
    }
}
