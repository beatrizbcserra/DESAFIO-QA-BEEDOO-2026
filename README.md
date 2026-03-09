# DESAFIO-QA-BEEDOO-2026

**Este repositório contém a documentação técnica e os resultados dos testes realizados para o módulo de cadastro e listagem de cursos da aplicação Beedoo QA Challenge.**

## 1. Objetivo da Aplicação
Com base na análise exploratória, o objetivo principal da aplicação é fornecer uma interface simples para a gestão de cursos, permitindo que administradores cadastrem novas ofertas (presenciais ou online) e visualizem a lista de cursos ativos para controle interno ou divulgação.

## 2. Principais Fluxos Disponíveis
Cadastro de Cursos: Fluxo onde o usuário preenche informações como nome, descrição, instrutor, datas e número de vagas.

- Listagem de Cursos: Visualização centralizada de todos os cursos que foram salvos no sistema.

- Exclusão de Cursos: Funcionalidade destinada a remover um curso da base de dados (atualmente identificada como um ponto de falha).

## 3. Pontos Críticos para Teste
Identifiquei os seguintes pontos como os mais vitais para garantir a qualidade do sistema:

- Validação de Dados de Entrada: Garantir que o sistema não aceite campos obrigatórios vazios ou formatos inválidos (ex: vagas negativas ou nomes numéricos).

- Regras de Negócio de Datas: Impedir a criação de cursos com datas de término anteriores às de início.

- Persistência de Dados: Confirmar se, após o cadastro, o curso realmente aparece na listagem e se a exclusão funciona corretamente.

- Interface e Usabilidade: Verificar a integridade visual da aplicação (UI) e a correção de textos (Copy).

## 4. Documentação de Testes (Planilha)
Acesse o planejamento completo, incluindo Cenários de Teste, Casos de Teste (TC) e Relatórios de Erros (BUGs), no link abaixo:

[https://docs.google.com/spreadsheets/d/1mW2hnzqK0_HNqApEXoqEELVaFSFXLPqcFhSQXtXXsHY/edit?usp=sharing]

## 5. Evidências de Execução
Todos os prints e gravações de tela que comprovam os testes realizados e os bugs encontrados estão organizados na pasta compartilhada:

[https://drive.google.com/drive/folders/1ot3G8H-C9UYuyZeZ329w02r_dzc5fQAD?usp=sharing]

## 6. Resumo de Bugs Encontrados
Durante o ciclo de testes, foram registrados 6 bugs, sendo os principais:

- BUG-01: Permissões de cadastro com campos obrigatórios em branco.

- BUG-02: Falta de validação lógica em campos de data.

- BUG-06: Falha funcional no botão de exclusão de cursos.
