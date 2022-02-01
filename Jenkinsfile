pipeline{
agent any
stages{
stage('deploy to dev'){
  when{
    branch 'develop'
  }
steps{
echo "deploy to dev servers"
}
}

stage('deploy to uat'){
  when{
    branch 'release'
  }
steps{
echo "deploy to uat servers"
}
}

  
stage('deploy to prod'){
  when{
    branch 'main'
  }
steps{
echo "deploy to prod servers"
}
}
}
}
