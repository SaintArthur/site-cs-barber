# Pendências — landing page do CS Barber

Levantado em 23/09/2026. Números conferidos por contagem no `index.html` desta data.

---

## 1. A página afirma "grátis" e o FAQ nega

**5 ocorrências** de "grátis": "Testar 7 dias grátis", "Quero testar 7 dias
grátis", "Começar meu teste grátis". Mas o FAQ responde que as condições do
período são combinadas na conversa com o comercial, e os comentários do arquivo
registram que a condição do trial não está fechada — foi por isso que o "Sem
cartão" saiu dos selos.

A página afirma e nega na mesma tela. **Decidir:** é grátis ou não?

## 2. Sem aviso de privacidade (LGPD)

O formulário coleta nome, e-mail, WhatsApp e dados do negócio. Zero ocorrências de
"LGPD" ou "privacidade" no arquivo. Vale para os três sites.

## 3. WhatsApp pessoal em 8 links

São 8 links para `wa.me/5527999941710`, anotado no próprio arquivo como o número
pessoal do Matheus, a trocar pelo comercial antes de escalar verba. Contar também
a ocorrência montada no JavaScript do formulário.

---

## Já resolvido aqui, pendente nos outros

**O trial de 7 dias já está corrigido neste repositório** (commit `b848887`, 19
pontos). O `index.html` tem 24 ocorrências de "7 dias" e nenhuma de "15 dias".

O **site-cs-bella ainda tem 23 ocorrências dizendo 15 dias** — é a pendência mais
urgente do conjunto, porque muda o que o visitante lê. Ao corrigir lá, valem as
duas armadilhas que apareceram aqui:

1. Os comentários de briefing dentro do arquivo também afirmam 15 dias; reescreva
   a regra junto com o número visível, senão o próximo a abrir o arquivo desfaz.
2. O FAQPage do JSON-LD precisa continuar idêntico palavra por palavra ao FAQ
   visível, ou o rich result cai.

No **site-conecta-solucoes** há 3 menções a 15 dias, e duas delas são prazo de
**implantação**, não de teste — exigem decisão antes de mexer. Detalhe no
`PENDENCIAS.md` de lá.

## Dois fatos que evitam erro

1. **`csbarber.conectasolucoes.ia.br` é o app de verdade**, com login e agenda. O
   endereço que aparece na barra dos mockups do hero e da dobra das telas está
   **correto** — não troque para `www.csbarber.ia.br`, que é esta landing page.
2. **O arquivo usa CRLF em todas as linhas.** Ao inserir linha nova com `\n` puro,
   o arquivo fica com finais de linha misturados. Normalize com
   `s.replace(/(?<!\r)\n/g,"\r\n")` no fim de cada script que editar.

## Publicação

Este site publica por **AWS** (`./publicar.sh` → S3 + CloudFront). O push para o
GitHub **não** coloca nada no ar — e hoje a página no ar ainda anuncia 15 dias,
embora o repositório já diga 7.

A ferramenta de limpeza passou de Python para **Node** — confirme `node --version`
na máquina que tem o `aws` antes de rodar.
