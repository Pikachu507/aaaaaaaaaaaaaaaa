# GoalDistrict — loja para Vercel

Projeto React + Vite com design responsivo e páginas de categorias, favoritos, pesquisa, modal de produto, escolha de tamanhos e carrinho funcional no navegador.

## Publicar na Vercel

1. Extrai o ZIP e coloca a pasta `goaldistrict` num repositório GitHub.
2. Na Vercel, escolhe **Add New → Project** e importa o repositório.
3. Framework: **Vite** (detetado automaticamente). Build command: `npm run build`. Output directory: `dist`.
4. Clica em **Deploy**.

## Executar localmente

```bash
npm install
npm run dev
```

## Editar

- `src/main.jsx`: categorias, subcategorias, produtos, preços, funcionalidades e textos.
- `src/style.css`: cores, layout e animações de interface.
- `public/images/hero.png`: fotografia enviada para o banner.
- `public/images/logo.png`: logótipo enviado.

## Antes de vender

**Este é um frontend de demonstração, não uma loja pronta a receber pagamentos.** Os produtos são exemplos ilustrados, sem fotos reais, stock ou base de dados. O checkout e login são informativos e não processam transações. Configura um backend de encomendas, catálogo real, inventário, autenticação, pagamentos (ex. Stripe), regras da promoção LEVA 5 PAGA 4, envios, termos legais e privacidade antes de iniciar vendas. A barra promocional é apenas visual.

Não declares que os produtos são oficiais ou réplicas sem verificares o catálogo real.
