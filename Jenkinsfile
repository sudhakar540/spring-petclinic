pipeline{
 agent any
 stages ('Example1')
 {
   stage ('example')
   {
   steps
   {
      sh 'echo sudhakar1'
   }
   }
   stage ('example2')
   {
    agent {label 'JnlpTestNode'}
   steps
   {
      sh 'echo sudhakar2'
   }
   }
 }
}
