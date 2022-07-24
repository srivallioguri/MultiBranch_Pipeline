node('master')
{
  stage('Continuos Download')
  {
    git 'https://github.com/srivallioguri/MultiBranch_Pipeline.git'
  }
  stage('Continuos build branch_two')
  {
    sh 'echo "In branch_two"'
  }
}
