## Introdução

Este documento detalha o processo de criação de uma instância de máquina virtual EC2 na Amazon Web Services (AWS), com o intuito de proporcionar um ambiente para aprendizado e experimentação em computação na nuvem.

## Objetivo

O principal objetivo é explorar os recursos da AWS criando uma instância EC2, que servirá como base para práticas de administração de sistemas, desenvolvimento de software, e outras atividades educativas relacionadas à tecnologia da informação.

## Materiais

- Conta ativa na Amazon Web Services (AWS).
- Computador com acesso à internet.
- Protocolo SSH para conexão.

## Método

### Passo 1: Criação da Instância EC2

1. Acessar o console da aws e ir para aba de instanciar uma EC2. Após, precisamos adicionar um nome ao servidor (ponderada semana 03), selecionar o sistema operacional desejado (windows), selecionar o tipo de instaância (t2.micro), criar um par de chaves de segurança (ponderada-03) e selecionar a quantidade de memória desejada.

<img src="/ponderada-03/Captura de tela 2024-02-25 222242.jpg">

### Passo 2: Acesso SSH à Instância

1. Endereço IP Público: Localize o endereço IP público da sua instância EC2 no painel de controle da AWS.
2. Conexão SSH: Utilize o PuTTY ou o terminal SSH para conectar à instância usando o endereço IP público e a chave privada associada.
