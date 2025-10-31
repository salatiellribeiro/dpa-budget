DPA Budget (PWA)
================
App leve para iPhone (instalável) para controlar orçamento de projetos de pintura. Funciona offline e salva dados no aparelho.

Como publicar e instalar no iPhone
----------------------------------
1) Faça upload desta pasta para um repositório no **GitHub**.
2) Ative o **GitHub Pages** (Settings → Pages → Source: Deploy from a branch → main → /root).
3) Abra a URL no **Safari do iPhone**.
4) Toque em **Share → Add to Home Screen (Adicionar à Tela de Início)**.
5) Abra o app "DPA Budget" no iPhone.

O que ele faz
-------------
- Projetos (contrato ex-GST).
- Despesas por categoria.
- Mão de obra (horas × tarifa).
- Invoices/claims (Deposit/Progress/Final/Variation) com % do contrato e status (Draft/Sent/Paid).
- Dashboard com Receita, Pago, Custos e Margem %.
- Backup/Restore para JSON (iCloud/Files).

Observações
-----------
- O app é local (sem servidor). Para multi-dispositivo, evoluir para um backend (ex: Supabase/Firestore).
- GST hoje é referência; cálculos principais usam valores ex-GST.
- Personalize em `index.html` conforme precisar.