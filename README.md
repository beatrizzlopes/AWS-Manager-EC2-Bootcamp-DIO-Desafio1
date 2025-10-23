# AWS-Manager-EC2-Bootcamp-DIO-Desafio1
## AWS EC2 MANAGER
Este repositório possui minhas anotações e insights adquiridas durante o módulo de Gerenciamento de Instâncias EC2, incluindo o desafio, do bootcamp Santander Code Girls com a DIO, focado em computação em nuvem com AWS.

## Objetivo do Desafio

Diagrama.

Criar um repositório público no GitHub contendo: 

Um arquivo README.md detalhado;

Quaisquer arquivos adicionais que sejam relevantes para documentar sua experiência;

Opcionalmente, capturas de tela relevantes organizadas em uma pasta /images.

## Material presente no repositório
Arquivo README.md: Explicação detalhada do desafio, insights e anotações principais do módulo de Gerenciamento de Instâncias EC2.

anotaçoesdesafio1.md: Registro do passo a passo do desafio.

Imagens: Captura de tela do Desafio.

## Anotações Principais
### Instância correta

Escolher a instância correta na AWS é crucial para garantir eficiência, escalabilidade e economia nos gastos com nuvem
  
### Amazon EBS
Elastic Block Store (EBS), é uma storage altamente confiável que pode ser anexado em qualquer instância EC2. Toda instância possui um volume de armazenamento. Com a EBS conseguimos ter a capacidade de expansão de forma rápida,com apenas alguns clicks.

Resumo:  É um tipo de storage em bloco, que funciona como um disco rígido virtual que você pode anexar a uma instância EC2.
Permite armazenar dados de forma confiável e expandir a capacidade rapidamente.

Storage = lugar para guardar dados no computador ou na nuvem.

Snapshot = é uma cópia de segurança de um volume de armazenamento (como o EBS). Ele salva o estado dos dados naquele momento, permitindo que você recupere ou duplique o volume depois.

Restore = é o processo de recuperar os dados a partir de um snapshot, ou seja, restaurar o volume para o estado em que estava quando o snapshot foi feito.

### Amazon S3

Amazon S3 (Amazon Simple Storage Service) é um serviço de armazenamento de objetos em movem oferecido pela AWS.

### Criação e uso de imagens AMI

A imagem de máquina da Amazon (AMI): No Amazon EC2, uma AMI é uma imagem de máquina virtual pré-configurada, que inclui as informações necessárias para iniciar uma instância, como o sistema operativo, o servidonde aplicações e as aplicações.

Tipos de AMI: Existe diferentes tipos, incluindo Amazon Linux, Windows e outros. Escolhe-se uma AMI com base nos requisitos da aplicação e do sistema.

Diferença AMI e Snapshot:

AMI: faz o backup de um servidor inteiro, incluindo todos os volumes EBS anexados.

Snapshot: é uma cópia pontual de um determinado volume. você pode tirar snapshot de seus volumes EBS e salvá-los no armazenamento S3.

## Diagrama de interação dos serviços AWS.


### Insights



### Referências





