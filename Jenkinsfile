node {
            stage('Checkout SCM'){
                git branch 'SP2', url:
            }
            
            stage('Install node modules'){
                     sh "npm install"
            }
            stage('Bulid'){
                    sh "npm run bulid"
            }
            stage('deploy'){
                     sh "pm2 restart all"
            }
}
