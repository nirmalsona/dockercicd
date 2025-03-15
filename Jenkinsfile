pipeline{

agent{

docker{image 'ubuntu'} // using lighweight container

args '-u root'

}


stages{

stage( 'testdemo' ){

steps {

sh 'whoami'

}

}

}


}



