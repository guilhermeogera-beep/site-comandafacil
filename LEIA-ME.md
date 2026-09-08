# Site do ComandaFácil

Uma página só, sem build e sem biblioteca — as mesmas regras dos outros
projetos. Abre em qualquer lugar, funciona com internet ruim, e dá para
mexer com um editor de texto.

## Antes de publicar

Abra o `index.html` e procure por:

- `5519974206363` — o WhatsApp, no formato internacional só com dígitos:
  `55` + DDD + número. Exemplo: `5511987654321`. Troque TODAS as ocorrências
  (são 3 botões, mais a linha de aviso no topo do arquivo).
- `guilhermeogera@gmail.com` — o e-mail de contato.

## Onde ele mora

```
appcomandafacil.com.br         -> o sistema  (outro repositório)
site.appcomandafacil.com.br    -> este site
```

Não pode ser `www`: o GitHub Pages trata o `www` como apelido do domínio
principal e manda os dois para o mesmo lugar. Por isso `site.`.

## Como publicar

1. Repositório novo no GitHub, com estes arquivos
2. **Settings -> Pages** -> Branch `main`
3. No registro.br, um CNAME: nome `site`, valor `guilhermeogera-beep.github.io`
4. **Settings -> Pages -> Custom domain** -> `site.appcomandafacil.com.br`
5. Espere o certificado e marque **Enforce HTTPS**

## As telas da página não são fotos

São o CSS do próprio sistema, reproduzido à mão. Sai mais leve que imagem,
fica nítido em qualquer tela, e não envelhece junto com um print antigo.

Se um dia a tela do sistema mudar de cara, esta página precisa ser
atualizada junto — é o preço de não usar foto.
