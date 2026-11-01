# Orçamento 2.0 — instalação

O 2.0 roda em paralelo ao Orçamento atual: endereço próprio e pasta própria no OneDrive (`Orcamento Familiar 2.0`). Nada do que for feito em um afeta o outro.

## Arquivos

- `index.html` → o site. Este vai para o GitHub.
- `carga_inicial_orcamento2.json` → seus dados (contas, saldos, histórico, lançamentos, orçamento). **Nunca envie para o GitHub**, porque o repositório é público. Guarde no computador ou no OneDrive.

## 1. Publicar no GitHub (5 minutos)

1. No GitHub, crie um repositório novo, por exemplo `orcamento2`, **público**.
2. **Add file → Upload files** → envie só o `index.html` → **Commit changes**.
3. **Settings → Pages** → Branch `main`, pasta `/ (root)` → **Save**.
4. Anote o endereço: `https://SEU-USUARIO.github.io/orcamento2/`.

## 2. Autorizar o novo endereço na Microsoft (2 minutos)

Use o mesmo aplicativo já registrado, só acrescentando o endereço:

1. **entra.microsoft.com** → Aplicativos → Registros de aplicativo → abra o “Orçamento da Família”.
2. **Autenticação** → em “Aplicativo de página única”, clique em **Adicionar URI** → cole o endereço do passo 1 (com a barra no final) → **Salvar**.

## 3. Conectar e carregar os dados (Elvis)

1. Abra o endereço → **Ajustes** → Modo **OneDrive pessoal** → cole o mesmo ID do aplicativo → **Salvar e conectar**.
2. A pasta `Orcamento Familiar 2.0` é criada no seu OneDrive.
3. Em **Ajustes → Carga inicial**, escolha o arquivo `carga_inicial_orcamento2.json`.

## 4. Acesso da Jaque

1. No OneDrive, compartilhe a pasta `Orcamento Familiar 2.0` com o Hotmail dela, com permissão **Pode editar**, e copie o link.
2. No celular dela: endereço do 2.0 → Ajustes → OneDrive pessoal → mesmo ID do aplicativo + link da pasta → Salvar e conectar.

## 5. Primeiros ajustes

- **Cadastros → Contas:** preencha os dias de fechamento e vencimento dos cartões (é o que define em qual fatura cada compra cai) e as metas das reservas (valor e prazo).
- **Cadastros → Contas:** quando chegar o extrato, informe o saldo devedor do Empréstimo Jaque - Viacredi em 30/09/2026 (saldo inicial negativo) e o saldo das Cotas Viacredi.
- **Lançamentos → “Ver” no aviso amarelo:** confira as duas transferências marcadas.
- **Prompt da IA:** copie o novo prompt para o ChatGPT e o Gemini (ele mudou: agora usa contas, cartões, para quem e projeto).

## Uso no dia a dia

- **Compra no cartão:** lance na conta do cartão. Ela entra no mês da fatura.
- **Fatura venceu:** no Painel, botão **Pagar** ao lado do cartão. Vira uma transferência da conta corrente para o cartão.
- **Parcela de empréstimo, aporte, resgate:** Novo lançamento → Transferência.
- **Conferência:** digite o saldo do extrato em “Informado”. Nas aplicações e reservas, isso gera o rendimento; nos empréstimos a pagar, os juros.
- **Orçamento:** metas por categoria e programados (salários, contas fixas, parcelas). Quando um programado acontecer, toque em **Lançar**.
