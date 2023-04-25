node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repository', 'dockerHub') {

        def customImage = docker.build("dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
