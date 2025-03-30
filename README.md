# 💭 Análise de Sentimentos com Language Studio no Azure AI

## 📋 Descrição

Este projeto utiliza o Azure AI Language Studio para analisar sentimentos em feedbacks de usuários de um app de compras de mercado via delivery. A técnica de Processamento de Linguagem Natural (NLP) identifica se as opiniões são positivas, negativas ou neutras, ajudando a melhorar a experiência do usuário.

### ⚙️ Ambiente: Criação e Configuração

Foi criado um recurso no Language Service dentro do Azure, configurado na região apropriada e com o tier gratuito (F0).
No Language Studio, o recurso foi vinculado a uma conta do Azure, garantindo as permissões adequadas.

### 📊 Dados: Preparação e Processamento

Foi utilizado a ferramenta "Analyze sentiment and opinions", no Language Studio, e feito upload de um arquivo de texto com as sentenças.
Os dados consistem em 10 sentenças relacionadas a feedbacks de clientes em uma loja de mercado via delivery.
Após isso, foi processado o texto para identificar os sentimentos gerais dos clientes.

### 📑 Feedback: Resultado esperado

Os resultados esperados eram: Positivo, Negativo e Neutro.
Outros pontos importantes sobre os feedbacks seriam: Usabilidade, Preços ofertados, Canais de ajuda e etc.

### 💡 Análise: Insights
Após analisar as sentenças, alguns insights importantes foram analisados:

Os sentimentos sobre a usabilidade do aplicativo sempre tendem a ser mais positivos.
![Image](https://github.com/user-attachments/assets/73bdb033-a9f1-4cb0-9408-b7839ddfaa70)

Frustrações nas entregas sempre tendem a ser mais negativos.
![Image](https://github.com/user-attachments/assets/225054de-af50-4348-a63f-35703d99deb6)

Atendimento e suporte ao cliente sempre tendem a ser mais neutro, por conter uma condição "mas" ou "porém".
![Image](https://github.com/user-attachments/assets/01e6eeca-499c-44f0-b8fe-4a8f091619eb)

## ✨ Conclusão: Azure AI no contexto de Análise de Sentimentos

A análise de sentimentos com o Azure AI Language Studio oferece uma forma poderosa de extrair insights valiosos de dados textuais não estruturados. A capacidade de identificar não apenas o sentimento geral, mas também aspectos específicos mencionados, permite uma compreensão mais profunda da experiência do cliente.
Este projeto demonstra como configurar e utilizar essa tecnologia para análise de feedback de clientes em uma loja de mercado via delivery, mas as mesmas técnicas podem ser aplicadas em diversos setores e casos de uso.
