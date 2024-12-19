pipeline {
   agent any
   tools {
       matlab 'latest'
   }
    stages {
      stage('Run MATLAB Command') {
        runMATLABCommand "ver"
      }
    }
  }
}
