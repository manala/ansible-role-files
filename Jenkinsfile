#!groovy

node('docker') {

    stage 'Checkout'
    checkout scm

    stage 'Wheezy'
    sh 'make test@wheezy'

    stage 'Jessie'
    sh 'make test@jessie'

}
