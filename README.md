# Trilha HTML - Dio.me
## Módulo 02 - HTML I - Conceitos Básicos

## Especificações
1. Site de uma clínica médica
2. Menu de navegação:
    - Página Principal
    - Sobre a clínica
    - Horário de Atendimento
    - Contato
3. Temas abordados:
- Formulários
- Estruturação e formatação de texto
- Mídias
- Tabelas

### Estrutura das páginas

As páginas seguem uma estrutura semelhante a image abaixo.

![Estrutura](https://i.stack.imgur.com/9jI6f.gif)

 - **Menu** de navegação;
 - **Header** : Imagem diferente em cada página;
 - **Content**: Conteúdo de cada página.
 - **Footer**: Informações de contato;

### Página Principal
Uma breve descrição sobre a clínica.

### Sobre a clínica
Um texto falando sobre a clínica.

### Horário de Atendimento

Um pequeno texto falando sobre os serviços, e uma tabela de preços, onde cada linha é um serviço, com o preço de cada um de acordo com os dias da semana.

|Serviços |Segunda a Sexta | Sábados | Feriados |
|---|---|---|---|
|Clínica geral | 08h - 19h  | 08h - 14h | 08h - 14h  |
|Psicologia | 08h - 19h  | 08h - 14h | 08h - 14h  |
|Pediatria | 08h - 19h  | 08h - 18h | - |
|Oftalmologia | 08h - 19h  | 08h - 18h | - |
|||||

### Contato
    - Os telefones de contato (celular e whatsapp)
    - Endereço completo da clínica
    - Um Iframe com o Google Maps apontando o endereço da clínica
    - Um formulário de contato com:
        - Nome (type="text")
        - E-mail (type="email")
        - Assunto (type="text")
        - Mensagem (textarea)
        - Botões de envias e limpar formulário
