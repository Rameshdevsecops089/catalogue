@Library('jenkins-shared-library') _

def configMap = [
    Project : "roboshop",
    component : "catalogue"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main
    nodejsEKSPipeline(configMap) // by default it will call, call function inside this pipelilne
}
else{
    echo "please proceed with PROD Process"
}
