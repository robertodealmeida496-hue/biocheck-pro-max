# Pregnancy Test Pro — PWA Clone

## Ficheiros
- `index.html` — App completo (todas as telas + PayPal + multi-idioma)
- `manifest.json` — Manifesto PWA (instalável como app)
- `sw.js` — Service Worker (cache offline)

## Idiomas incluídos
🇧🇷 Português | 🇺🇸 English | 🇪🇸 Español | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇹 Italiano

## Telas
1. **Home** — Advanced Digital Detection + botão START
2. **Scanning** — Fingerprint animado + barra de progresso
3. **Payment** — PayPal Smart Buttons (€4.99) + cartão
4. **Success** — Confirmação de pagamento

## PayPal
- Client ID: `AYuCohLKaabwimk_5Rngf6Dglx8sOJBmFxsj91wUUNIzrntGnVFyJIjY_uSEP5cUaGSZ868QGkyFwNt-`
- Moeda: EUR (€4.99)
- Botões: PayPal + Cartão de crédito/débito

## Deploy
1. Coloque os 3 ficheiros num servidor HTTPS (obrigatório para PWA)
2. Acesse via browser mobile → "Adicionar à tela inicial"
3. O app instala como PWA nativo

### Opções gratuitas de host:
- **Netlify**: arraste a pasta em netlify.com/drop
- **Vercel**: `vercel deploy`
- **GitHub Pages**: faça upload para repositório público

## Notas
- O PayPal SDK requer HTTPS em produção
- Para ícones, adicione `icon-192.png` e `icon-512.png` (logo vermelho com onda)
