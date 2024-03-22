pipeline{
agent any
stages{
stage('stage1')
{
steps{
sh 'rm -rf /var/www/html/*'
}
}
      stage('stage2')
     { 
        steps{
          sh"mv * /var/www/html"
}
}
}
}
