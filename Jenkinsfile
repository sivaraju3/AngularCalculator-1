node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("sivaraju369/dockerweb2")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
