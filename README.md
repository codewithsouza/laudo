# Laudo Técnico Contábil - Análise de DIFAL

Sistema web para análise de DIFAL (Diferencial de Alíquota) em prestações de serviço de transporte.

## 📋 Sobre o Projeto

Este sistema permite analisar operações de transporte de cargas e identificar anomalias fiscais relacionadas ao DIFAL, incluindo:

- Análise de contribuintes vs não contribuintes do ICMS
- Identificação de anomalias cadastrais
- Cálculo automático do DIFAL
- Visualização interativa dos dados

## 🚀 Deploy

### Deploy Automático (Railway/Render/Vercel)

O projeto está configurado para deploy automático como site estático:

1. **Railway**: Conecte o repositório GitHub
2. **Render**: Use o template "Static Site"
3. **Vercel**: Conecte o repositório

### Deploy Manual

```bash
# Instalar dependências
npm install

# Executar localmente
npm start

# Build para produção
npm run build
```

## 📁 Estrutura do Projeto

- `laudo.html` - Laudo principal com análise de DIFAL
- `laudo2.html` - Painel de análise de ocorrências fiscais
- `package.json` - Configurações do projeto
- `nixpacks.toml` - Configuração de build

## 🛠️ Tecnologias

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- Chart.js (Gráficos)
- Node.js (Servidor estático)

## 📊 Funcionalidades

- ✅ Cálculo automático de DIFAL
- ✅ Identificação de anomalias fiscais
- ✅ Gráficos interativos
- ✅ Filtros por categoria
- ✅ Busca em tempo real
- ✅ Interface responsiva

## 🔧 Configuração

O sistema não requer banco de dados - todos os dados são carregados via JavaScript no frontend.

## 📝 Licença

MIT License
