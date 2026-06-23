# CodeStudy Pro 10/10

Versão executando o roadmap.

## O que foi adicionado

### Sistema de estudo
- XP por aula.
- Níveis.
- Sequência diária.
- Meta diária configurável.
- Progresso por curso.
- Revisão espaçada automática: 1, 3, 7 e 15 dias.

### Aulas
- 71 aulas organizadas por trilha.
- Java, HTML, CSS, JavaScript, Apex e Backend.
- Explicação de onde usar.
- Termos importantes explicados.
- Código exemplo.
- Guia de leitura linha por linha.
- Erros comuns.
- Exercícios por tipo.
- Desafio por aula.

### Exercícios
- Múltipla escolha com correção.
- Completar conceito.
- Corrigir erro.
- Exercício de código.
- Respostas salvas localmente.

### Projetos guiados
- Sistema Bancário em Java.
- Cadastro de Alunos em Java.
- Portfólio HTML/CSS.
- Lista de Tarefas com LocalStorage.
- API REST de Usuários.
- Trigger Apex Bulkificada.

### Editor
- Editor por desafio.
- Editor por aula.
- Salvamento local.
- Verificação local por requisitos.

### IA
- Tela de IA opcional via NVIDIA API.
- Campo para API Key.
- Campo para modelo.
- Botão para pedir ajuda sobre aula.
- Botão para revisar projeto.
- Tratamento de erro quando API/modelo/WebView falhar.

## O que foi corrigido
- Tudo em www/index.html.
- Sem service worker.
- Sem arquivos JS/CSS externos.
- Workflow com Node 24.
- Workflow com Java 21.
- Capacitor fixado em 7.4.3.
- Validação se index.html entrou no Android.

## Como gerar APK
1. Extraia o ZIP.
2. Envie os arquivos para um repositório novo.
3. Vá em Actions.
4. Rode Build Android APK.
5. Baixe em Artifacts.
6. Desinstale versões antigas antes de instalar.

## Honestidade
Essa versão é forte para estudo offline/mobile. A IA depende da API NVIDIA e da disponibilidade do modelo escolhido.


## O que foi adicionado nesta versão

### IA contextual por aula
- A IA agora detecta a aula atual.
- Envia para a IA: curso, título da aula, nível, objetivo, termos importantes, código, exercícios e desafio.
- Botão "Tirar dúvida".
- Botão "Explicar aula".
- Botão "Gerar desafio personalizado".
- Botão "Corrigir meu código".
- Prompt orientado para não entregar tudo pronto nos desafios.
- Resposta em PT-BR com foco didático.

### Limite honesto
A IA depende de API Key NVIDIA, internet, modelo disponível e WebView permitindo requisições. Se falhar, o app continua funcionando offline.
