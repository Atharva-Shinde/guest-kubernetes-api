# guest-kubernetes-api

A scaffolded Kubernetes operator.

1. Create a directory, and then run the init command inside of it to initialize a new project: 
    
    `kubebuilder init --domain my.domain --repo my.domain/guestbook`
2. Scaffold an API: 

    `kubebuilder create api --group webapp --version v1 --kind project-name`
