# Ficha de Coleta de Correias Ucelo

Aplicação estática para preenchimento e exportação em PDF da ficha de coleta de dados de correias transportadoras.

## Publicação na Vercel

Este repositório já inclui `vercel.json` para publicar a ficha na raiz do domínio (`/`) apontando para o HTML principal.

1. Importe o repositório na Vercel.
2. Use as configurações padrão de projeto estático, sem comando de build.
3. Publique o projeto.

## Proteção do conteúdo

Por ser uma página estática executada no navegador, o HTML/CSS/JavaScript sempre pode ser inspecionado por quem acessa o site. Para reduzir cópia indevida, o projeto inclui:

- Marca d'água repetida `UCELO` no documento e no PDF gerado.
- Headers no Vercel para impedir indexação e arquivamento por robôs de busca.
- Headers básicos de segurança para reduzir exposição desnecessária.

Para proteção forte de regras de negócio ou código proprietário, mova essas partes para um backend/API autenticado.
