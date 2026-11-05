# Parsec

Portfólio pessoal: desenvolvedor backend .NET e Java, com experiência em infraestrutura, integrações e DevOps.

Site estático (HTML, CSS e JavaScript puros), bilíngue PT/EN, publicado no GitHub Pages.

## Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | O site inteiro: estilos, conteúdo e scripts (fundo de estrelas e troca de idioma) |
| `.nojekyll` | Faz o GitHub Pages servir os arquivos como estão, sem processar com Jekyll |

## Rodar localmente

Abra o `index.html` no navegador, ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

## Editar o conteúdo

- Os textos em português estão direto no HTML.
- As traduções em inglês ficam no objeto `en` dentro do `<script>` no fim do `index.html`. Cada chave corresponde a um atributo `data-i18n` no HTML.
- Os trechos com a classe `placeholder` (em azul no site) são campos a preencher: nome, contatos e métricas.

## Publicar

1. Crie um repositório público no GitHub e envie este projeto.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O site fica em `https://<usuario>.github.io/<repositorio>/`.
   Para usar `https://<usuario>.github.io/`, o repositório precisa se chamar `<usuario>.github.io`.

## Próximos passos

- [ ] Preencher nome, e-mail, LinkedIn, GitHub e currículo
- [ ] Adicionar métricas reais aos estudos de caso
- [ ] Revisar o que pode ser publicado sobre o trabalho na T2S
- [ ] Domínio próprio (`.dev` ou `.com.br`)
- [ ] Migrar para Next.js e Vercel
