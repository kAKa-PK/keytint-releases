# KeyTint

**Deixe o seu teclado com as cores do seu wallpaper.** by K7Corp

O KeyTint sincroniza os LEDs de teclados **MonsGeek / Akko** com o wallpaper do Windows ou do
**Wallpaper Engine**. Cada tecla pega a cor da parte da imagem que fica sobre ela.

## Recursos
- Gradiente por tecla que segue a imagem do wallpaper
- Cor única, cor ao vivo com transição suave e captura de tela
- Efeitos nativos do teclado (respiração, onda, chuva...) na cor do wallpaper *(experimental)*
- Modo noite: reduz o brilho num horário
- Regras por aplicativo: troca de perfil quando um jogo ou app entra em foco
- Reconhece o modelo do teclado e desenha as teclas certas
- Perfis, apagar o LED ao bloquear o PC, iniciar com o Windows
- Atualização automática por este repositório

## Como baixar e usar
1. Abra a aba **[Releases](https://github.com/kAKa-PK/keytint-releases/releases/latest)** e baixe o `KeyTint-<versão>.rar` (a pasta completa).
2. Extraia, entre na pasta `KeyTint` e abra o `KeyTint.exe`. Se o Windows mostrar "O Windows protegeu seu PC", clique em
   **Mais informações → Executar assim mesmo**. O programa ainda não é assinado digitalmente.
3. O painel abre e reconhece o teclado. Fechar a janela deixa o KeyTint na bandeja, perto do relógio.

O `KeyTint.zip.sha256` da release traz o SHA-256 do pacote de atualização, caso queira conferir.

## Compatibilidade
Teclados MonsGeek/Akko com fabricante `0x3151`, por cabo USB. Testado no **Fun60 Pro**.
Outros modelos devem funcionar se usarem o mesmo protocolo. Se algo vier errado, abra uma
[issue](https://github.com/kAKa-PK/keytint-releases/issues) com o nome do modelo que aparece no topo do painel.

## Avisos
- Cada troca de wallpaper grava na memória do teclado. Por isso existe um intervalo mínimo entre
  gravações (padrão: 20 s) e um contador no painel.
- Projeto independente, **não afiliado** à MonsGeek nem à Akko. Os nomes pertencem aos seus donos.
- Uso por sua conta e risco.

## Créditos
Protocolo do teclado baseado em engenharia reversa da comunidade:
[monsgeek-rgb](https://github.com/Lightning-13/monsgeek-rgb) (Lightning-13, MIT) e
[monsgeek-akko-linux](https://github.com/echtzeit-solutions/monsgeek-akko-linux) (echtzeit-solutions).

© 2026 K7Corp. Todos os direitos reservados.
