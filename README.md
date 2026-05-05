# Caderno Temático: O Ecossistema Moderno do Desenvolvimento Mobile

## 🎯 Contexto e Objetivos
Este repositório foi criado para consolidar meus estudos sobre as tecnologias fundamentais para o desenvolvimento de aplicações móveis modernas. O objetivo é construir uma base sólida de conhecimento, partindo da lógica dinâmica do JavaScript, passando pela segurança do TypeScript, até a produtividade do framework React Native com Expo.

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM e embasar meus estudos, selecionei as seguintes fontes oficiais e referências de mercado:
1. [Documentação Oficial do React Native](https://reactnative.dev/docs/getting-started) - Fundamentos de componentes nativos.
2. [Documentação do TypeScript](https://www.typescriptlang.org/docs/) - Referência para implementação de Type Safety.
3. [Documentação do Expo](https://docs.expo.dev/) - Fluxo de trabalho e acesso a APIs nativas.
4. [Repositório React Native Community](https://github.com/react-native-community) - Melhores práticas e bibliotecas padrões.

## 🧠 Engenharia de Prompts e "Cicatrizes"
Nesta seção, registro o raciocínio por trás do uso da IA para acelerar o aprendizado:

* **Prompt Estratégico:** > "Explique a diferença prática entre usar 'any' e 'unknown' no TypeScript em um contexto de resposta de API no React Native."
* **Variação Testada:** > "Como tipar adequadamente um objeto retornado pelo método .map() vindo de uma Promise no React?"

### 🛠️ Troubleshooting (Cicatrizes):
* **Filtro de Modernidade:** Inicialmente, a IA gerou exemplos utilizando *Class Components*. Precisei ajustar o prompt para: *"Refatore os exemplos utilizando estritamente Functional Components e React Hooks"*.
* **Contexto Mobile:** Em dúvidas sobre JavaScript puro, a IA focava em Web (DOM). Corrigi solicitando que as analogias fossem voltadas para o motor *Hermes* do React Native.
* **Terminologia:** Notei que traduções literais de termos técnicos (como "Safe Typing") causavam confusão. Instruí a IA a manter termos da indústria em inglês com explicações em português.

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **JavaScript:** O motor dinâmico. O foco aqui foi entender o comportamento assíncrono (`Promises` e `async/await`), essencial para não travar a interface do usuário (UI) durante chamadas de API.
* **TypeScript:** A camada de segurança. Aprendi que o uso de `Interfaces` e `Types` não é apenas burocracia, mas uma forma de documentar o código e evitar erros de execução (Runtime).
* **React Native & Expo:** A combinação que permite alta performance com baixo custo de configuração inicial. O Expo atua como um facilitador para acessar recursos como câmera e GPS sem precisar mexer em código nativo Java/Swift inicialmente.

### 2. Glossário
* **Type Safety:** Garantia de que uma variável respeitará seu tipo durante todo o ciclo de vida.
* **Superset:** Linguagem que contém todas as funcionalidades de outra, adicionando novos recursos (TS > JS).
* **Hot Reloading:** Tecnologia que permite ver alterações no código em tempo real no dispositivo físico ou simulador.

### 3. Prompts Reutilizáveis para Revisão
* ` "Resuma os principais hooks do React Native (useState, useEffect) com exemplos práticos de UI." `
* ` "Crie um checklist de 5 pontos para migrar um componente React Native de JS para TS." `
