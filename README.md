# Currículo IA

> Gerador inteligente de currículos adaptados para vagas específicas usando IA

## 📋 Sobre o Projeto

Este projeto utiliza inteligência artificial para adaptar currículos conforme a descrição da vaga, mantendo a experiência profissional original e evitando repetição de palavras-chave.

## 🚀 Como Funciona

### Fluxo de Uso

1. Prepare seu currículo base no arquivo `index.html`
2. Cole a descrição da vaga no arquivo `post.md`
3. Utilize o seguinte prompt com um modelo IA:

```
Seja um tech recruiter e com base no arquivo index.html gere outro arquivo idêntico, 
porém adaptando ao contexto da vaga que está no arquivo post.md, 
evite usar palavras-chave já existentes, não altere nada na experiência profissional, 
a vaga é para a posição de Júnior, não use a palavra especialista
```

## ⚠️ Importante

**Sempre use um prompt novo** para cada geração, evitando cache e garantindo adaptação genuína.

## 📁 Estrutura do Projeto

```
.
├── index.html     # Seu currículo base
├── post.md        # Descrição da vaga
└── README.md      # Este arquivo
```

## 💡 Dicas

- Mantenha seu currículo base o mais genérico possível
- Inclua palavras-chave relevantes em `post.md`
- Teste com diferentes vagas para melhores resultados
- Para gerar o curriculo em PDF, execute o html e imprima

---

**Desenvolvido com IA** ✨