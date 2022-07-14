pipeline{
agent any
stages{
stage(compile){
steps{
git credentialsId: 'aa281686-b7f2-4591-9421-a36a7de26d72', url: 'https://github.com/NavaneethKalkeri/my13threpo.git'
sh 'mvn compile'
}}}}
