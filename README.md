💰 Sistema de Gestão Financeira Modular (Python)
Este é um protótipo de software para gerenciamento de finanças pessoais, desenvolvido como parte do projeto acadêmico no Eniac. O foco principal do desenvolvimento foi criar uma base sólida de back-end com persistência de dados, tratamento de erros e uma arquitetura modular que facilite a manutenção e futura expansão para uma API.
🚀 Funcionalidades
Gerenciamento de Transações: Cadastro completo de receitas e despesas com descrição, valor, data, categoria e status.
Dashboard (Balanço Geral): Cálculo automático de total de receitas, total de despesas e saldo líquido atualizado em tempo real [Conversa Anterior].
Extrato Detalhado: Exibição formatada e organizada de todas as movimentações financeiras [Conversa Anterior].
Gestão Orçamentária: Permite configurar limites de gastos por categoria (ex: lazer, alimentação). O sistema emite alertas automáticos caso o teto definido seja ultrapassado ao cadastrar uma despesa [Conversa Anterior].
Persistência de Dados: Todos os dados e configurações são salvos localmente em formato JSON, garantindo que as informações não sejam perdidas ao fechar o programa [Conversa Anterior].
Segurança de Entrada: Implementação de tratamento de exceções (try-except) para validar entradas numéricas e evitar travamentos por dados inválidos [Conversa Anterior].
🛠️ Tecnologias Utilizadas
Python 3.x
JSON (para persistência de dados)
Git/GitHub (para controle de versão e colaboração)
📁 Estrutura do Projeto
O projeto segue um padrão profissional de modularização:
main.py: Arquivo de entrada do sistema, responsável pelo loop do menu e interação direta com o usuário [Conversa Anterior].
operacoes.py: Módulo central que contém toda a lógica de negócio, funções de cálculo, manipulação de arquivos e listas globais [Conversa Anterior].
dados_financeiros.json: Arquivo gerado automaticamente para armazenamento estruturado das informações [Conversa Anterior].
📸 Demonstração
(Dica: Arthur, tire prints do seu terminal funcionando e adicione as imagens na pasta do seu projeto, renomeando-as conforme abaixo para que apareçam aqui)
Menu Principal
Alerta de Limite de Gastos
🧑‍💻 Minha Participação Específica
Como responsável pela arquitetura lógica e back-end do projeto, minhas principais contribuições foram:
Desenvolvimento da Lógica Central: Criação das funções de processamento financeiro e cálculos de saldo [Conversa Anterior].
Implementação da Persistência: Estruturei o fluxo de leitura e escrita no arquivo JSON, garantindo que o sistema funcione como um banco de dados local robusto [Conversa Anterior].
Refatoração Modular: Realizei a separação do código em múltiplos arquivos (main.py e operacoes.py), seguindo padrões de mercado para organização e escalabilidade [Conversa Anterior].
Tratamento de Erros e UX: Implementei loops de validação com try-except para garantir que o software seja resiliente a falhas de digitação do usuário [Conversa Anterior].
Gestão de Versão: Responsável pela configuração do ambiente Git, criação do .gitignore para manter o repositório limpo e gestão de commits organizados [Conversa Anterior].
Como rodar o projeto
Clone o repositório:
Acesse a pasta:
Execute o sistema:
