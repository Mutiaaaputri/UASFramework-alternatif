pipeline { 
    agent any 
    stages { 
        stage('Clone Repository') { 
            steps { 
                git 'https://github.com/Mutiaaaputri/UASFramework-alternatif.git' 
            } 
        } 
        stage('Install Dependencies') { 
            steps { 
                echo'run'
            } 
        } 
        stage('Run Ansible Playbook') { 
            steps { 
             echo'testing
            } 
        } 
    } 
    post { 
        success { 
            echo 'Deployment successful!' 
        } 
        failure { 
            echo 'Deployment failed!' 
} 
} 
} 
Jenkins file berfungsi untuk mengkonfigurasikan pipeline pad program yang dibuat. 
Buat file lagi Namanya hosts
