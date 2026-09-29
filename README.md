# ATKFUT — Landing pages (2 variações)

Duas variações de landing page inspiradas em [atkfornecedor.com](https://atkfornecedor.com/), com copy ajustada para reduzir riscos de reprovação em Google Ads e TikTok Ads.

- `versao-a-ledger/` — visual escuro, estilo painel/dashboard, com simulador interativo de faturamento.
- `versao-b-catalogo/` — visual claro, estilo editorial/catálogo, com tabela de exemplo em vez de simulador.

Cada pasta é um site estático independente (`index.html` + `style.css`), sem dependências de build — basta abrir o `index.html` ou servir a pasta.

## Análise de conformidade (resumo)

**🔴 Crítico — Bens falsificados / propriedade intelectual.**
O site original vende réplicas de camisas de clubes usando marcas de terceiros (Nike, Adidas, Umbro, escudos de clubes) e se descreve como "Fornecedor Oficial". Isso se enquadra na política de **Counterfeit Goods** do Google Ads e na de **Propriedade Intelectual / Bens Falsificados** do TikTok Ads — ambas proíbem anúncios de réplicas não licenciadas de marcas registradas, independentemente do texto usado na página. **Nenhuma mudança de copy resolve isso.** A correção real exige produtos licenciados ou remoção de marcas/escudos de terceiros da comunicação e do material de anúncio.

**🟠 Alto — Promessas de ganho financeiro não substanciadas.**
Frases como "Lucre R$80 a R$130 por camisa" e valores fixos de lucro mensal (R$9.240, R$12.000/mês) caracterizam alegação de renda de oportunidade de negócio. O Google Ads restringe fortemente esse tipo de alegação (política de *Misrepresentation* / unrealistic earnings claims); o TikTok Ads exige aprovação prévia para a categoria *Business Opportunity* e não permite valor de lucro específico sem comprovação. Nas duas versões, os números viraram **faixas ilustrativas com aviso ao lado do valor**, não afirmações categóricas.

**🟡 Médio — Linguagem de urgência/escassez sem verificação.**
"Vagas de revenda abertas" foi removido/suavizado nas duas versões.

## O que foi ajustado nas duas versões

- Nenhuma menção a "fornecedor oficial" — trocado por "fornecedor atacadista".
- Nenhum valor de lucro apresentado como promessa fixa — sempre como exemplo/simulação com aviso.
- Nenhuma marca de clube ou fabricante esportivo aparece na página.
- Bloco de aviso legal visível na página (não só no rodapé).
- Disclaimer completo no rodapé sobre não afiliação e variação de resultados.

## Pendências antes de publicar/anunciar de verdade

1. Substituir o CNPJ placeholder pelo CNPJ real da empresa.
2. Decidir o que fazer quanto às imagens de produto (réplicas com marca de terceiros) antes de rodar tráfego pago — isso é o ponto que mais arrisca suspensão de conta.
3. Se for anunciar como "oportunidade de negócio" em qualquer plataforma, verificar se a categoria exige aprovação prévia (é o caso do TikTok Ads).
4. Revisar com jurídico/contador antes de publicar valores financeiros, mesmo como exemplo.
