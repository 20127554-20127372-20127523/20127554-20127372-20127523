node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("201275542012737220127523/20127554-20127372-20127523:1.1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
};