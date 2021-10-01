Fork criado para executar os exercícios de Kubernetes da KubeDev

O arquivo Dockerfile está dentro da pasta src e utiliza python:3.8-alpine

O arquivo manifesto está dentro da pasta k8s.

Devido a minha conexão lenta de internet, infelizmente pra subir a imagem linuxlite/rotten-potatoes precisei remover alguns arquivos .png do projeto e o requisito Pillow. Dessa forma imagem ficou com 57.1MB, caso contrário o Docker Hub sempre retornava "authentication required" com imagens maiores que isso.
