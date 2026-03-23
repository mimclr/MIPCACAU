# Monitoramento de Pragas e Doenças do Cacau

Aplicação web em React, preparada para publicação em GitHub e empacotamento no Median.co para geração de APK Android.

## Funcionalidades

- Cadastro de fazendas
- Cadastro de talhões vinculados à fazenda
- Avaliação fitossanitária com protocolo padrão de 20 plantas por hectare
- Histórico com edição e exclusão
- Armazenamento local no dispositivo via localStorage
- Exportação em Excel
- Exportação em PDF
- Botão externo para o site da Labor Rural
- Layout moderno com estética rural e referência ao cacau
- Fonte Montserrat

## Instalação local

```bash
npm install
npm run dev
```

## Build de produção

```bash
npm install
npm run build
```

A pasta gerada será `dist/`.

## Publicação no GitHub

1. Crie um repositório novo no GitHub.
2. Envie os arquivos deste projeto.
3. Faça o build com `npm run build`.
4. Publique o conteúdo da pasta `dist` em um hosting web.

Pode usar:
- GitHub Pages
- Netlify
- Vercel
- qualquer hospedagem estática

## Uso no Median.co

1. Após publicar o app web, copie a URL pública.
2. No Median.co, crie um novo app a partir da URL.
3. Configure nome, ícone, splash e permissões Android.
4. Gere o APK ou AAB.

## Observações técnicas

- Nesta versão MVP o armazenamento é local no navegador do dispositivo.
- Se o usuário limpar os dados do app ou navegador, os registros podem ser perdidos.
- Para uma versão mais robusta, o próximo passo é migrar para IndexedDB e incluir backup/importação.

## Próximos aprimoramentos sugeridos

- Fotos por avaliação
- Geolocalização
- Backup e restauração
- Dashboard analítico
- Configuração de protocolos
- Login por consultor
