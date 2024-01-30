# Coding Test - Data Engineer

Olá, candidato(a)! Estamos muito animados por você ter chegado até aqui e considerar se juntar à nossa equipe inovadora no PsiDoFuturo!

Aqui, valorizamos profundamente a excelência técnica e a honestidade. Este teste é uma oportunidade para você mostrar suas habilidades e paixão. Queremos que seja um reflexo autêntico do seu trabalho, por isso pedimos que seja você mesmo a realizar o teste. Claro, entendemos a importância de pesquisar e aprender, então sinta-se à vontade para usar o Google ou o ChatGPT para auxiliá-lo. O mais importante é que você compreenda o que está fazendo e revise seu trabalho no final. 

Boa sorte e esperamos que você aproveite este desafio!


## Introdução

Este teste é projetado para avaliar suas habilidades e conhecimentos como Data Engineer. Você deverá criar uma pipeline ETL em Python para processar dois conjuntos de dados fornecidos e armazenar os dados transformados em um banco de dados Postgres local.

## Arquivos de Dados

Você trabalhará com dois arquivos CSV, localizados no arquivo `data.zip`:

1. **Clientes:** Contém informações sobre clientes, incluindo IDCliente, Nome, CPF, Email, Endereço e Data de Nascimento.
2. **Transações:** Contém detalhes de transações, incluindo IDTransacao, IDCliente, DataPagamento, detalhes do produto e método de pagamento.

Note que alguns dados podem estar faltando ou em formatos inconsistentes.

## Requisitos da Pipeline ETL

### Extração (E)
- Carregue os dados dos arquivos CSV.

### Transformação (T)
- Limpe e transforme os dados, conforme necessário.
- Assegure que os dados estejam consistentes, padronizados e prontos para serem armazenados no banco de dados.

### Carregamento (L)
- Salve os dados transformados em tabelas apropriadas em um banco de dados Postgres local.
- Estruture as tabelas de forma a refletir as relações entre clientes e transações.
- Fique à vontade para criar mais tabelas se achar necessário.

## Entrega do Teste

- Crie um repositório no GitHub para o seu projeto.
- Faça commits regulares para demonstrar o progresso do seu trabalho.
- Inclua um arquivo `README.md` no repositório, detalhando:
  - Uma breve descrição do projeto.
  - Instruções claras sobre como configurar e executar sua pipeline ETL.
  - Quaisquer suposições ou decisões de design tomadas durante o desenvolvimento.

## Critérios de Avaliação

- Qualidade do código: legibilidade, uso de boas práticas, comentários e documentação.
- Eficiência da pipeline ETL: correção no processamento dos dados, tratamento de casos especiais e performance.
- Organização e estrutura do repositório GitHub.

## Prazo de Entrega

- O teste deve ser concluído e enviado para avaliação até [inserir data].

**Boa sorte!**
