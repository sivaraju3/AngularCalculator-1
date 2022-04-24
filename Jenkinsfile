node {

    checkout scm

    docker.withRegistry('', 'dockerhub') {

        def customImage = docker.build("sivaraju3/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
