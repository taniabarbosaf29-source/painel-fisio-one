# Como Colocar no GitHub

## Pré-requisitos
- Conta no GitHub (crie em github.com se não tiver)
- Git instalado no seu computador

## Passo a Passo

### 1. Criar Repositório
1. Vá para github.com
2. Clique em "+" → "New repository"
3. Nome: `painel-fisio-one`
4. Descrição: "Sistema de gerenciamento de serviços para Fisio One"
5. Deixe como Public (para acessar via link)
6. Clique "Create repository"

### 2. Upload dos Arquivos (Opção A - Via GitHub Web)
1. No seu repositório, clique "Add file" → "Upload files"
2. Arraste os arquivos:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Clique "Commit changes"

### 3. Upload dos Arquivos (Opção B - Via Git Command Line)
```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/painel-fisio-one.git
cd painel-fisio-one

# Copie os arquivos para a pasta
# (index.html, README.md, .gitignore)

# Adicione e faça commit
git add .
git commit -m "Adicionar painel Fisio One"
git push origin main
```

### 4. Ativar GitHub Pages (para acessar direto no navegador)
1. No repositório, vá em "Settings"
2. No menu esquerdo, clique "Pages"
3. Em "Source", selecione "Deploy from a branch"
4. Em "Branch", selecione "main" → "root"
5. Clique "Save"
6. Espere 1-2 minutos

### 5. Seu Link Fica
```
https://seu-usuario.github.io/painel-fisio-one/
```

## Atualizar Depois
Para fazer mudanças depois:

```bash
# Entre na pasta
cd painel-fisio-one

# Faça as alterações nos arquivos

# Upload
git add .
git commit -m "Descrição das mudanças"
git push origin main
```

## Troubleshooting

**Pergunta: Posso compartilhar o link com meus fisios?**
Sim! Qualquer pessoa com o link consegue usar o painel.

**Pergunta: Os dados ficam salvos na nuvem?**
Não! Os dados ficam no navegador de cada pessoa. Cada um tem seus próprios dados.

**Pergunta: Preciso de senha para acessar?**
Não, qualquer pessoa com o link acessa. Se quiser proteger, você teria que usar um servidor (mais complexo).
