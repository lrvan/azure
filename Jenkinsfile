node {
    try {
        sh 'az login'
        sh 'az list accounts'
    } catch (err) {
        echo "Failed: ${err}"
    } finally {
        sh 'az logout'
    }

//   input 'Login to AZ portal'

}
