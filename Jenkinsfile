node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("sivaraju369/dockerweb3")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
