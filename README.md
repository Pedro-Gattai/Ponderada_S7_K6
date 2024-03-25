# Ponderada_S7_K6
# Relatório de Teste de Carga - k6

## Introdução
Este relatório descreve os testes de carga realizados no endpoint [Insira o endpoint] da nossa aplicação. Os testes foram realizados usando a ferramenta k6.

## Tecnologia k6
k6 é uma ferramenta de teste de carga open-source que simula tráfego de usuários em uma aplicação para verificar como o sistema se comporta sob carga. Ele usa scripts JavaScript para definir os testes de carga.

## Instruções de execução:

1. Acesse o respositorio do grupo: ``` https://github.com/Inteli-College/2024-T0003-ES09-G03 ```

2. acessar a pasta ``` backend/src/k6 ```

3. Rodar no terminal ``` loadUpdateCustomer.js ```

## Endpoint sendo testado

O endpoint a ser testado é o ``` employer/updateEmployer ```

<img src="./Captura de tela de 2024-03-22 09-58-13.png"> </img>

## Explicando a tecnologia

O k6 é uma ferramenta de teste de desempenho projetada para testar a resistência e a eficiência de aplicações web. O k6 simula um monte de visitantes (chamados usuários virtuais) chegando e usando a aplicação ao mesmo tempo para ver como ela se comporta.

Você diz ao k6 o que esses usuários virtuais devem fazer, como navegar por páginas, fazer login ou postar comentários, usando um script escrito em JavaScript. Então você roda o k6, e ele executa esse script, muitas vezes em paralelo, para imitar muitos usuários reais.

Enquanto o teste está rodando, o k6 coleta informações sobre quanto tempo cada ação leva, se houve erros, e outras estatísticas importantes. No final, ele te dá um relatório para que você possa entender se a sua aplicação é rápida, estável e capaz de lidar com muitas pessoas ao mesmo tempo, ou se ela vai ficar lenta e frustrar seus usuários em momentos de grande acesso.

## Conceitos aprendidos

Navegando pela página de requisições HTTP no k6, eu pude captar vários conceitos fundamentais para a realização de testes de carga e desempenho em aplicações web. Aprendi como o k6 permite simular interações de usuário com uma aplicação ao fazer requisições HTTP. Entendi melhor como estruturar requisições, configurar parâmetros e checar respostas, que são peças-chave para avaliar a robustez de uma aplicação.

O aprendizado se estendeu para a análise de métricas que o k6 fornece após os testes. Agora sei como interpretar tempos de resposta e taxas de erro para identificar gargalos. Esses insights são vitais para otimizar a performance da aplicação e garantir que ela possa suportar um grande número de usuários sem degradar a experiência do usuário.
