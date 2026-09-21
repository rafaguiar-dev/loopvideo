# LoopVideo

Ferramenta de desktop (Windows) para **criadores que trabalham com IA**: transforma uma foto de uma pessoa em um vídeo de fala em loop contínuo (padrão de 2 min 30 s), pronto para usar como avatar em VSLs, criativos e vídeos longos — sem cortes visíveis e sem edição manual.

Começa como LoopVideo; a ideia é crescer para um kit de utilidades do dia a dia de quem cria com IA.

## O que ele faz

1. Você solta uma imagem (ou várias) e escolhe o gênero da pessoa.
2. O app gera os trechos de vídeo com IA (Kling, via conta Magnific/Freepik), monta o loop com emenda invisível e entrega o `FINAL_2m30.mp4` na sua pasta de vídeos.
3. Fila com várias imagens, retomada automática se fechar no meio, opções avançadas (modelo, resolução, formato) e estimativa de créditos antes de gerar.

## Instalar

1. Baixe o **`Instalar-LoopVideo-x.y.z.exe`** da [última release](../../releases/latest).
2. Execute. Não precisa de permissão de administrador; instala em `%LOCALAPPDATA%\LoopVideo` e cria o atalho.
3. Abra o LoopVideo e conecte sua conta Magnific (login abre no navegador).

O Windows SmartScreen pode avisar sobre "aplicativo desconhecido" na primeira vez: **Mais informações → Executar assim mesmo**.

## Atualizar

O app avisa sozinho quando sai uma versão nova e atualiza com um clique (baixa só o pacote de atualização, sem o ffmpeg). Se preferir, baixe o `Atualizar-LoopVideo-x.y.z.exe` da release e execute.

## Requisitos

- Windows 10/11 64 bits
- Conta Magnific com créditos (cada loop custa ~900 créditos no padrão)
- Internet

## Licença de uso

Uso interno / sob autorização. O aplicativo verifica a licença da máquina em um servidor; o administrador pode ativar ou desativar computadores a qualquer momento.

---

Desenvolvido por [rafaguiar.dev](https://rafaguiar-dev.github.io/).
