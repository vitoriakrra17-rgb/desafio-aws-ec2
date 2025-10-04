# desafio-aws-ec2
Projeto 1 Dio- CodeGilrs Santander

Este projeto tem como objetivo consolidar os conhecimentos adquiridos no laboratório sobre gerenciamento de instâncias EC2 na AWS, documentando o processo, aprendizados e insights obtidos.

EC2 são máquinas virtuais da AWS onde podemos separar ou corpartilhar aquela infraestrutura (IAAS) e pagamos por ela de forma rápida e segura.
Dividem - se em diversas instâncias que precisam ser estudadas de acordo com o tipo de projeto para a melhor alocação de recursos. 
Podem ser utilizados algumas ferramentas de otimização de custos como: Desligar instâncias não utilizadas em horarios comerciais, remoção de recursos ociosos e escalonamento de recursos tanto verticalmente como horizontalmente. 

Tipos de instâncias : Sob demanda (geralmente usadas em ambiente de teste), Instâncias reservadas e Instâncias Spot.

Geralmente as maquinas EC2 utilizam de duas ferramentas : o Amazon EBS e o Amazon S3.

Amazon EBS nada mais é que um tipo de 'HD externo' aclopado a VM para o aumento da capacidade de armazenamento e processamento. 
É utilizado geralmente para bancos de dados.

Amazon S3 nada mais é que um serviço de aramazenamento de objetos em nuvems utilizado geralmente para armazenar, organizar e recuperar grandes volumes de dados. 
Dividido em algumas classes sendo duas principais: S3 Standart ( para recuperação de dados em até 3 meses) e S3 Glacier ( para dados acimas de 90 dias)

AMI - Amazon Machine Image são modelos pré-configurado contendo sistema, aplicativos e dados essenciais AWS.
Snapshots EBS - serviço que fornece armazenamentos em bloco fiável sendo utilizado dentro da EC2. Ele funciona como uma forma de backup e é possivel configurar a frequência que são realizadas as snapshots. 
