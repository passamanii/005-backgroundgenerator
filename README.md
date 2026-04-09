# Fundo Mágico - Background Generator

Uma aplicação web inovadora que transforma descrições em texto em backgrounds CSS incríveis usando inteligência artificial! O **Fundo Mágico** é um gerador de backgrounds inteligente que permite descrever o background que você imagina em linguagem natural, e a IA transforma sua visão em código HTML e CSS prontos para uso. Perfeito para designers, desenvolvedores e criadores que buscam inspiração ou soluções rápidas para seus projetos.

## Recursos Principais

-  **Geração por IA**: Transforma descrições em texto em backgrounds CSS funcionais
-  **Preview em Tempo Real**: Veja o resultado imediatamente na tela
-  **Código Copiável**: Acesso direto ao código HTML e CSS gerado
-  **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
-  **Rápido e Intuitivo**: Interface simples e fácil de usar

##  Tecnologias

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **API**: n8n Cloud (Webhooks + AI)
- **Fontes**: Google Fonts (Bebas Neue, Roboto Mono)
- **Versionamento**: Git

## Como Começar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para acessar a API)

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/005-backgroundgenerator.git
   cd 005-backgroundgenerator

2. Abra no navegador
Abra o arquivo index.html diretamente no seu navegador.

### Como Usar

1. Descreva seu Background

Digite uma descrição na caixa de texto principal
Exemplos:
"Um gradiente que vai do azul claro ao azul escuro com efeito degradê"
"Fundo com animação de partículas coloridas em movimento"
"Padrão geométrico em tons de rosa e roxo"

2. Gere o Background

Clique no botão "Gerar Background Mágico"
Aguarde a IA processar sua descrição

3. Visualize o Resultado

Veja o preview do seu background na seção de preview
Copie o código HTML e CSS disponibilizados

4. Use em Seu Projeto

Integre o código gerado em seus projetos web

## Estrutura do Projeto
```
005-backgroundgenerator/
├── index.html                 
├── src/
│   ├── css/
│   │   ├── reset.css         
│   │   ├── style.css         
│   │   └── responsive.css   
│   ├── js/
│   │   └── script.js      
│   ├── img/
│   │   ├── bg.JPG         
│   │   └── wand.ico         
│   └── pages/              
├── .git/                  
├── .gitignore             
└── README.md
```

## Como Funciona

```
┌─────────────────────┐
│   Usuário digita    │
│   descrição em      │
│   linguagem natural │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────────┐
│  JavaScript envia para  │
│  Webhook n8n (POST)     │
└──────────┬──────────────┘
           │
           ▼
┌──────────────────────┐
│  IA Generativa       │
│  (Claude/GPT) processa
│  e gera CSS + HTML   │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────────┐
│  API retorna código      │
│  HTML e CSS              │
└──────────┬───────────────┘
           │
           ▼
┌───────────────────────────┐
│  Frontend exibe:          │
│  - Preview do background  │
│  - Código HTML            │
│  - Código CSS             │
└───────────────────────────┘
```

## Contribuições

Contribuições são bem-vindas! Para contribuir:

- Faça um Fork do projeto
- Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
- Commit suas mudanças (git commit -m 'Add some AmazingFeature')
- Push para a branch (git push origin feature/AmazingFeature)
- Abra um Pull Request

### Autor
Feito por Luís Felipe Passamani, estudante de programação.
