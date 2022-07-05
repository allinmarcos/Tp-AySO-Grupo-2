# Tp-AySO-Grupo-2

## Functionality of the files
- Dockerfile: creates a nginx image and copies the index.html file in the required path (usr/share)
- namespace.yml: Creates a namespace named: tp-ayso-grupo-2
- deployment.yml: Creates a deployment with one replica uploading the Dockerfile image from our Docker Hub repository. It also uses the namespace.yml
- index.html: creates a h1 with the following text: "Hola Mundo, somos el grupo 2 de la UTN" 

## Usage
1. Open the terminal in the folder that you have the repository files.
2. Run the deployment.yml in the linux terminal using this command.
```bash
kubectl apply -f ./deployment.yml
```

## Contributors
- [Máximo Pepa](https://github.com/MaxiPepa)
- [Marcos Allín](https://github.com/allinmarcos)
- [David Medina](https://github.com/odavidmedina)
- [Santiago Fiore](https://github.com/Fioresantiago)
