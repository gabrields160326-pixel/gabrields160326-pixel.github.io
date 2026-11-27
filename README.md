# Projeto Viva Sua Profissão

Template inicial da disciplina **Administração de Websites** (Curso Técnico em Desenvolvimento de Sistemas).

## Estrutura de Pastas

```text
├── index.html               # Página inicial do portal
├── css/
│   └── style.css            # Estilos globais e variáveis de cores
├── img/                     # Pasta para banner e imagens do grupo
└── pages/
    ├── habilidades.html     # Habilidades, formação e mercado
    ├── materiais.html       # Banner, proposta de e-book e esboço de landing page
    └── sobre.html           # Mapa do site e justificativa técnica
```

## Como publicar no GitHub Pages (Aula 2)

1. Crie um repositório público no GitHub (ex.: `viva-sua-profissao`).
2. Envie todos os arquivos mantendo exatamente esta estrutura de pastas.
3. No repositório, acesse **Settings > Pages**.
4. Em **Source**, selecione `Deploy from a branch`, escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
5. Aguarde cerca de 1 minuto e acesse o link gerado (`https://seu-usuario.github.io/viva-sua-profissao/`).

## Regras de Ouro para Não Quebrar o Site

- **Nunca** use barra `/` no início de links ou imagens (use `css/style.css` e não `/css/style.css`).
- Nomeie imagens e arquivos sempre em **letras minúsculas, sem espaços e sem acentos** (ex.: `banner-principal.png`).

## Atividade 27/11/26
## Personas

1. Persona 1: Aluno em busca de fontes de pesquisas sobre Cibersegurança
1. Persona 2: Visitante que busca entender Cibersegurança
1. Persona 3: Dono de negocio que deseja  anunciar algo no site

## Tabela 

1. Código
2. Tipo
3. Descrição
4. Status

1. RF01 
2. Funcional
3. O usuário deve navegar entre todas as páginas pelo menu sem links quebrados. 
4. [x] implementado

1. RF02 
2. Funcional
3. -Organização do site sem quebra de logica
4. [ ] Planejado

1. RF03  
2. Funcional
3. -Melhora da ligação entre o código e o servidor 
4. [ ] Planejado

1. RNF01 
2. Não Funcional
3. O layout deve ser responsivo em telas de celular sem barra de rolagem horizontal.
4. [x] implementado

1. RNF02
2. Não Funcional
3. -O design tem de ser harmonia de cores com o assunto
4. [ ] Planejado

1. RN01
2. Regra de Negócio
3. -Não permite que algo seja anunciado sem aviso ou pagamento
4. [ ] Planejado

