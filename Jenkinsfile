pipeline {
    agent any
    stages{
        stage(Build){
           steps{
             echo  'hello world ..build step'
           }
        }
        stage (Deploy){
            steps{
             echo  'deploy ...'
           }
        }
        stage (Test){
             steps{
             echo  'Testing ..'
           }
        }
        stage (Release){
              steps{
             echo  'Release..'
           }
        }
    }
}
