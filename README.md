# Bot Multi-Uso

Este projeto implementa um bot para o Telegram com funcionalidades focadas em interações baseadas em links de redes sociais. Ele foi desenvolvido para baixar conteúdos (como vídeos) de plataformas específicas e compartilhar os resultados diretamente no chat.

---

## Funcionalidades Implementadas

### 1. Baixar conteúdo de links de redes sociais

O bot analisa mensagens enviadas por usuários e verifica se elas contêm links de redes sociais como:
- Instagram
- TikTok
- Reddit
- X (anteriormente Twitter)

Se o link for válido, o bot:
- **Baixa o conteúdo** usando a ferramenta [yt-dlp](https://github.com/yt-dlp/yt-dlp).
- **Envia o resultado** de volta no chat:
  - Para vídeos: retorna o arquivo de vídeo.
  - Para links inválidos ou erros: retorna uma mensagem de erro personalizada.

---