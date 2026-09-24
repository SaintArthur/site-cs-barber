# Pendências — landing page do CS Barber

Levantado em 23/09/2026 e atualizado no mesmo dia, depois das correções.

---

## Resolvido

- **Trial de 7 dias** em toda a página, inclusive no link do aviso sem
  JavaScript (o prazo ia codificado na URL, `15%20dias`, e escapou da primeira
  troca). Nenhuma ocorrência de "15 dias" nem de `15%20dias`.
- **WhatsApp**: os 7 links `wa.me` e o montado pelo JavaScript do formulário
  apontam para `5527999073651`, o comercial da Conecta — o mesmo do site
  institucional, por decisão do dono. O número pessoal do Matheus
  (`5527999941710`) saiu.
- **CNPJ** saiu do rodapé, por decisão do dono. A razão social ficou.
- **Aviso de privacidade (LGPD)** abaixo do botão do formulário: diz que o envio
  abre o WhatsApp (serviço da Meta) com a mensagem pronta, que ela só chega à
  Conecta Soluções quando a pessoa toca em Enviar, que o site não guarda os
  dados e que o contato serve só para falar do pedido. Se entrar webhook, o
  aviso tem que mudar junto.
- **Formulário**, testado ao vivo com saídas interceptadas:
  - WhatsApp colado ou autopreenchido com +55 ou com 0 na frente chegava como
    outro número; agora normaliza. Número de fora do Brasil ("+" e código de
    país) é aceito como digitado, de 8 a 15 dígitos. DDD 55 (RS) com um dígito
    a mais não vira outro número.
  - "Recebido!" aparecia antes de qualquer envio; agora a tela diz que falta
    tocar em Enviar no WhatsApp e oferece o link para reabrir a mensagem.
  - Selects sem escolha não entram mais na mensagem; "Outro" sai uma vez só e
    não vai quando desmarcado.
  - Campos com 16px (o iPhone dava zoom ao focar com 15px).
  - Sem JavaScript o botão fica desabilitado (antes fazia GET com os dados
    pessoais na URL); o `<noscript>` mantém o link direto para o WhatsApp.
  - Foco no primeiro campo inválido na ordem da tela; o erro some ao corrigir.

## Decidido pelo dono

- **"Grátis"**: o teste de 7 dias é grátis. Os botões continuam com "grátis" e,
  por decisão do dono, o FAQ ("As condições do período são combinadas na
  conversa com o comercial") fica como está.

## Dois fatos que evitam erro

1. **`csbarber.conectasolucoes.ia.br` é o app de verdade**, com login e agenda. O
   endereço que aparece na barra dos mockups do hero e da dobra das telas está
   **correto** — não troque para `www.csbarber.ia.br`, que é esta landing page.
2. O FAQPage do JSON-LD precisa continuar idêntico, palavra por palavra, ao FAQ
   visível, ou o rich result cai. Confira com script depois de mexer no FAQ.

## Publicação

Este site publica por **AWS** (`./publicar.sh` → S3 + CloudFront). O push para o
GitHub **não** coloca nada no ar: tudo acima só chega ao público depois de rodar
o `./publicar.sh` numa máquina com a credencial `aws` e Node. O script roda os 34
testes de `ferramentas/testar-limpeza.js` antes de enviar.
