pipeline{
     agent any

            stages{
               stage ('git-checkout'){
                                   steps{
                                         git "https://github.com/RajputA1/game-of-life.git"
}
}
               stage('mvn') {
			   steps {
			   sh "mvn package"
			   }
			   }
}
}
