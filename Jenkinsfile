#!groovy

node('docker') {

    stage 'Wheezy'
    sh 'make test@wheezy'

    stage 'Jessie'
    sh 'make test@jessie'

}
