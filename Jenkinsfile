pipeline(
  agent any
    stages{
      stage{'Build'}{
        steps{    
            echo "Build running"
            sh './gradlew build --no-daemon'
            archiveArtifactsartifacts:'dist/trainSchedule.zip'
            }
        }
    }
}
