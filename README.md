# AWS-Manager-EC2-Bootcamp-DIO-Desafio1
## AWS EC2 MANAGER
Este repositório possui o desafio diagrama de arquitetura e minhas anotações adquiridas durante o módulo de Gerenciamento de Instâncias EC2 do bootcamp Santander Code Girls com a DIO, focado em computação em nuvem com AWS.

## Objetivo do Desafio

Diagrama.

Criar um repositório público no GitHub contendo: 

Um arquivo README.md detalhado;

Quaisquer arquivos adicionais que sejam relevantes para documentar sua experiência;

Opcionalmente, capturas de tela relevantes organizadas em uma pasta /images.

## Material presente no repositório
Arquivo README.md: Explicação detalhada do desafio e anotações do módulo de Gerenciamento de Instâncias EC2.

Imagens: Captura de tela do Desafio.

## Anotações
### Instância correta

Escolher a instância correta na AWS é crucial para garantir eficiência, escalabilidade e economia nos gastos com nuvem
  
### Amazon EBS
O Elastic Block Store (EBS) é um serviço de armazenamento em blocos altamente confiável que pode ser anexado a qualquer instância EC2. Toda instância EC2 possui pelo menos um volume de armazenamento, e com o EBS é possível expandir essa capacidade de forma rápida e simples, com apenas alguns cliques.

Resumo:
O EBS é um tipo de armazenamento em bloco, que funciona como um disco rígido virtual que pode ser anexado a uma instância EC2. Ele permite armazenar dados de forma confiável e aumentar a capacidade de armazenamento de maneira ágil.

Storage: local para guardar dados, seja em um computador ou na nuvem.

Snapshot: é uma cópia de segurança de um volume de armazenamento (como o EBS). Ele registra o estado dos dados em um determinado momento, permitindo que você recupere ou duplique o volume posteriormente.

Restore: é o processo de recuperar os dados a partir de um snapshot, ou seja, restaurar o volume ao estado em que estava no momento em que o snapshot foi criado.

### Amazon S3

O Amazon S3 é um serviço de armazenamento de objetos em nuvem oferecido pela AWS. Ele permite armazenar e recuperar qualquer quantidade de dados, a qualquer momento e de qualquer lugar da internet, de forma segura, escalável e com alta durabilidade.

Conceitos principais:

Bucket:
É como uma “pasta” principal onde os arquivos (objetos) são armazenados. Cada bucket tem um nome único e pode conter um número praticamente ilimitado de objetos.

Objeto:
É o arquivo propriamente dito que você armazena no S3 (por exemplo: imagens, vídeos, documentos, backups etc.). Cada objeto contém os dados, os metadados e uma chave única (nome do arquivo dentro do bucket).

Classes de Armazenamento:
O S3 oferece diferentes classes de armazenamento, cada uma otimizada para um tipo de uso e custo:

S3 Standard: para dados acessados com frequência.

S3 Intelligent-Tiering: ajusta automaticamente a classe de armazenamento conforme a frequência de acesso.

S3 Standard-IA (Infrequent Access): para dados acessados ocasionalmente.

S3 Glacier / Glacier Deep Archive: para arquivamento e backup de longo prazo, com custo muito baixo.

Vantagens:

Alta durabilidade (99,999999999% ou “11 noves”).

Escalabilidade automática — armazene desde alguns megabytes até petabytes de dados.

Segurança e controle de acesso por políticas e permissões.

Integração fácil com outros serviços da AWS (como EC2, Lambda, CloudFront etc.).

### Criação e uso de imagens AMI

A AMI (Amazon Machine Image) é uma imagem pré-configurada usada para criar instâncias EC2.
Ela contém o sistema operacional, aplicações e configurações necessárias para iniciar um servidor.

Tipos de AMI: Amazon Linux, Windows, Ubuntu e outras.

AMI x Snapshot:

AMI: backup completo de um servidor (inclui todos os volumes EBS).

Snapshot: cópia pontual de um volume EBS, armazenada no S3.

Resumo da interação:
O usuário cria uma instância EC2 a partir de uma AMI → usa EBS para armazenamento → snapshots desses volumes são salvos no S3.

## Desafio diagrama de arquitetura
![Image Alt](https://github.com/beatrizzlopes/AWS-Manager-EC2-Bootcamp-DIO-Desafio1/blob/3bd3be6bae11f22235d84c5122af038e04ce78ce/imagens/Diagrama%20sem%20nome.drawio%20(4).png)

## Referências
https://web.dio.me/track/santander-code-girls-2025
Autora: Beatriz Lopes




