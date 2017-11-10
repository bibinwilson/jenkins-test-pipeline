node('master') {

    stage('BUILD') {
     echo "Hello World"
    }
    
    stage ('TESTS') {
    parallel(
      "Cart Tests": {
        echo "running cart tests "
      },
      "Discount Tests": {
        echo "running discount tests"
      }
    )
    }
    
    stage('DEPLOY') {
    echo "Hello World"
    }

    stage('VERIFY') {
    echo "Goodbye world"
    }
}
