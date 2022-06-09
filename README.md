# Tp-AySO-Grupo-2

- Dockerfile: creates a nginx image and copies the index.html file in the required path (usr/share)
- nginxG2.yml: Creates a container with the Dockerfile image and builds it in the port 8080:80
- namespace.yml: Creates a namespace named: tp-ayso-grupo-2
- deployment.yml: Creates a deployment with one replica uploading the Dockerfile image
- index.html: creates a H1 with the following text: "Hola Mundo, somos el grupo 2 de la UTN" 


- Considerations: We did what we could with the knowledge that we have and searched on the internet. It's not the best but at least we tried to make something that works. Hopefully we will improve it any time soon.