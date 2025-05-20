# Estrelas do Amanhã - Formulário de Matrícula

![image](https://github.com/user-attachments/assets/45d96484-195e-404c-ac79-33ccb58f9675)

## Visão Geral

Este projeto consiste em um formulário de matrícula online para a escola de educação infantil Estrelas do Amanhã. O formulário é intuitivo e responsivo, permitindo que pais ou responsáveis realizem a inscrição de seus filhos de forma rápida e segura.

## Funcionalidades Principais

* **Informações da Criança:** Coleta dados essenciais como nome completo, data de nascimento, sexo e informações médicas relevantes.
* **Certidão de Nascimento:** Permite o upload da certidão de nascimento da criança.
* **Endereço Residencial:** Solicita o CEP e, embora pré-preenchido com "Rua das Flores" e "São Paulo - SP" como exemplos , o campo de CEP é funcional para futuras integrações de busca de endereço. O número da residência é um campo obrigatório.
* **Informações do Responsável:** Coleta o nome do responsável legal, telefone de contato (com um placeholder de exemplo) e e-mail (com validação básica e feedback de erro).
* **Opções de Matrícula:**
    * Seleção do turno de estudo (Manhã ou Tarde).
    * Opção de inscrever a criança em atividades esportivas (Futebol, Basquete, Natação, Yoga, Volley, Boxe).
* **Termos e Condições:** Exige a concordância com os Termos e Condições e a Política de Privacidade da escola.
* **Ações:** Botões para "Salvar respostas" e "Fazer matrícula".

## Estrutura de Arquivos

* `assets/`: Contém todos os arquivos de mídia, como ícones, ilustrações e a logo da escola.
* `assets/icons/`: Armazena os ícones SVG utilizados no formulário.
* `assets/Illustration.svg`: Ilustração da professora com as crianças.
* `assets/logo.svg`: Logo da escola Estrelas do Amanhã.
* `styles/`: Contém todos os arquivos CSS para estilização do formulário.
* `styles/buttons.css`: Estilos específicos para os botões.
* `styles/checkbox.css`: Estilos para os elementos de checkbox personalizados.
* `styles/droparea.css`: Estilos para a área de upload de arquivos.
* `styles/fields/index.css`: Pode conter estilos específicos para grupos de campos.
* `styles/forms.css`: Estilos gerais para o elemento `<form>`.
* `styles/global.css`: Estilos globais e variáveis de cores e fontes.
* `styles/index.css`: Arquivo principal que importa todos os outros arquivos CSS.
* `styles/input.css`: Estilos para os elementos de input, textarea e select.
* `styles/layout.css`: Estilos para a estrutura principal da página (`#app`, `main`, `aside`).
* `styles/radio.css`: Estilos para os elementos de radio button personalizados.
* `index.html`: Arquivo HTML principal que estrutura o formulário.


## Tecnologias Utilizadas

* HTML5: Estrutura do formulário.
* CSS3: Estilização completa do formulário, incluindo layouts flexbox e grid.
* SVG: Utilização de ícones vetoriais para melhor escalabilidade e qualidade visual.
* Fontes do Google Fonts: Utilização da fonte 'Poppins' para uma tipografia moderna e legível.

* ## Como Usar

Para visualizar o formulário, basta abrir o arquivo `index.html` em um navegador web compatível.

## Considerações Futuras

* **Integração com Backend:** Implementar a lógica de envio dos dados do formulário para um servidor backend para processamento e armazenamento das matrículas.
* **Validação Avançada:** Adicionar validações mais robustas nos campos do formulário, incluindo formatos específicos (e.g., para CEP e telefone).
* **Busca de Endereço por CEP:** Integrar uma API de busca de CEP para preenchimento automático dos campos de endereço.
* **Funcionalidade "Salvar Respostas":** Implementar a funcionalidade para que os usuários possam salvar o progresso do formulário e completá-lo posteriormente.
* **Acessibilidade:** Realizar testes de acessibilidade para garantir que o formulário seja utilizável por todos os usuários, incluindo aqueles com deficiências.
* **Responsividade:** Embora o layout seja adaptável, realizar testes em diversos dispositivos e tamanhos de tela para garantir uma experiência de usuário consistente.

## Créditos

* Design e desenvolvimento por [Marcos Vinícius Do Amaral / Curso Rocketseat].
* Ícones utilizados de [Figma].
* Fonte 'Poppins' do Google Fonts.

## Licença

Este projeto está licenciado sob a **Licença MIT**.
