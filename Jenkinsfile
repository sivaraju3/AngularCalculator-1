node {

    checkout scm

    docker.withRegistry('https://github.com/sivaraju3/AngularCalculator-1.git', 'dockerhub') {

        def customImage = docker.build("sivaraju3/eccom369")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
