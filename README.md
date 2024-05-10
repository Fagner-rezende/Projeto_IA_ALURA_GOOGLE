# Guia do Futuro: Um Chatbot para Teste Vocacional

## Introdução
Bem-vindo ao **Guia do Futuro**, um chatbot interativo projetado para ajudar estudantes entre 15 e 20 anos a descobrir suas paixões e talentos. Utilizando a tecnologia de **IA da Google, o GEMINI**, este chatbot oferece uma experiência personalizada que guiará os usuários em uma jornada de autoconhecimento e sugere carreiras alinhadas com seus interesses e habilidades únicos.
## Funcionamento
**Configuração da API:** O código se conecta à API do Google Gemini utilizando uma chave de API,o modelo foi configurado e os parâmetros definidos de temperatura e filtros de segurança para gerar resultados seguros ao usuário.

**Interação Inicial:** O chatbot se apresenta ao usuário, solicita seu nome e explica brevemente o objetivo da interação.

**Ciclo de Perguntas:** É gerado um loop com 8 iterações que apresenta perguntas relevantes para entender os interesses e habilidades do usuário. Essas perguntas são geradas dinamicamente pelo Gemini a partir de um prompt específico que foi desenvolvido para fazer o Gemini agir da maneira mais precisa para que possamos obter um resultado satisfatório.

**Armazenamento de Respostas:** Cada resposta do usuário é adicionada ao histórico do chat do Gemini para contextualizar as próximas perguntas e a análise final.

**Sugestão de Carreiras:** Ao final do loop de perguntas, um prompt detalhado, contendo todo o histórico da conversa, é enviado ao Gemini. O modelo então analisa as informações e sugere 5 carreiras que se alinham com o perfil do usuário.

**Apresentação das Sugestões:** O chatbot apresenta as sugestões de carreira ao usuário de forma clara, concisa e com uma breve explicação do porque desta sugestão.

## Conclusão 
O **"Guia do Futuro"** oferece uma experiência interativa e personalizada para estudantes que buscam orientação vocacional. A integração com o Google Gemini garante perguntas relevantes e sugestões de carreira precisas, tornando o chatbot uma ferramenta valiosa para o autoconhecimento e planejamento do futuro.
