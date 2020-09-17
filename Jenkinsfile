pipeline{

stages{
stage('Build'){
steps{


 bat mvn install
}

}
stage('Deploy'){
steps{


 bat mvn clean package deploy -DmuleDeploy -Dusername=ptupakula -Dpassword=Siva@208
}

}

}
}