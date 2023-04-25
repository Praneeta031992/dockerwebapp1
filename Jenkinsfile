node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repository/docker/praneeta123/project1/general', 'dockerHub') {

        def customImage = docker.build("praneeta/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
