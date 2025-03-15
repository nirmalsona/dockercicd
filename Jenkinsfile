pipeline{

  agent none
  stages{

    stage ('Front-end'){
      agent{
        docker{ image 'node'}
      }

steps{
  sh ' node --version'
}

      stage ('Back-end'){
      agent{
        docker{ image 'maven'}
      }

steps{
  sh ' maven --version'
}
}
}
}

        

    
