# Destiny 2 Hub

**Destiny 2 Hub** is a Windows desktop app with configurable shortcuts for Destiny 2 movement macros and tools.

## Download

Download and run:


.net sdk 8.0: https://dotnet.microsoft.com/pt-br/download/dotnet/thank-you/sdk-8.0.420-windows-x64-installer

[Destiny2HubSetup.exe](https://github.com/AwokesD2/D2-Hub/releases/download/v1.0.0/Destiny2HubSetup.exe)


If Windows shows a security warning, choose to keep/run the file only if you downloaded it from this official repository:

`https://github.com/AwokesD2/D2-Hub`

## Portugues

### Antes de comecar

O **Destiny 2 Hub** funciona apenas quando o Destiny 2 esta aberto e em foco. Se voce clicar em outro programa, os atalhos ficam desativados automaticamente para nao atrapalhar sua digitacao.

### Como instalar e abrir

1. Baixe `Destiny2HubSetup.exe`.
2. Execute o instalador.
3. Abra o Destiny 2.
4. Deixe o Destiny 2 como a janela principal.
5. Confira se os modulos aparecem como **Pronto**.

Se o Destiny 2 estiver aberto como administrador, abra o Destiny 2 Hub tambem como administrador.

### Binds padrao recomendados no Destiny 2

| Acao no jogo | Bind |
| --- | --- |
| Slide | `Ctrl` |
| Power weapon | `3` |
| Special weapon | `2` |
| Primary weapon | `1` |
| Heavy swing | `RButton` |
| Light swing | `LButton` |
| Block | `C` |
| Super | `F` |
| Air move | `X` |
| Sprint | `Shift` |
| Powered melee | `C` |

Se seus binds forem diferentes, entre no menu **Settings** e altere os binds para combinar com o seu Destiny 2.

### Atalhos padrao

| Modulo | Atalho |
| --- | --- |
| Wish-Wall | `F3` |
| Warlock Skate | `F5` |
| Warlock Flat Skate | `F6` |
| Hunter Skate | `F7` |
| Hunter Flat Skate | `F8` |
| Rocket Fly | `B` |

### Status mais comuns

- **Pronto**: o atalho esta ativo e pode ser usado.
- **Aguardando foco**: o Destiny 2 esta aberto, mas outra janela esta selecionada.
- **Jogo fechado**: o Destiny 2 nao foi detectado.
- **Pausado**: a automacao foi pausada.
- **Conflito**: dois atalhos estao usando a mesma tecla.
- **Erro de bind**: algum bind configurado nao e valido.
- **Rodando**: o app esta executando um macro.

### Wish-Wall

1. Va ate a parede de wishes no Destiny 2.
2. Abra o menu **Wish-Wall** no app.
3. Escolha o desejo na lista.
4. Ajuste a **Sensibilidade**, se necessario.
5. Escolha a **Velocidade** entre `1` e `2`.
6. Deixe o Destiny 2 em foco.
7. Pressione o atalho configurado.

### Rocket Fly

O menu **Rocket Fly** executa uma sequencia rapida de click, movimento do rocket e granada.

Recomendado uma rocket com velocidade a partir de 40 exemplo: (Gjallahorn)

- Atalho padrao: `B`
- Deteccao padrao: `10.0`
- Bind da granada padrao: `Q`

### Configuracoes

As configuracoes ficam em:

`%APPDATA%\D2Hub\settings.json`

### Problemas comuns

- Se o atalho nao funciona, confira se o Destiny 2 esta em foco, se o app esta **Ativo** e se o modulo aparece como **Pronto**.
- Se aparecer **Aguardando foco**, clique no Destiny 2 e tente novamente.
- Se aparecer **Jogo fechado**, abra o Destiny 2 ou reinicie o app depois que o jogo estiver aberto.
- Se o macro apertar a tecla errada, corrija os binds em **Settings** e clique em **Salvar**.
- Se o Wish-Wall errar os simbolos, ajuste **Sensibilidade**, **Velocidade** e a posicao inicial da mira.
- Se o Rocket Fly ficar forte ou fraco demais, ajuste **Deteccao** no menu **Rocket Fly**.

## English

### Before you start

**Destiny 2 Hub** only works when Destiny 2 is open and focused. If you click another program, the shortcuts are automatically disabled so they do not interfere with typing.

### How to install and open

1. Download `Destiny2HubSetup.exe`.
2. Run the installer.
3. Open Destiny 2.
4. Make Destiny 2 the active window.
5. Check that the modules show **Ready**.

If Destiny 2 is running as administrator, open Destiny 2 Hub as administrator too.

### Recommended default Destiny 2 binds

| In-game action | Bind |
| --- | --- |
| Slide | `Ctrl` |
| Power weapon | `3` |
| Special weapon | `2` |
| Primary weapon | `1` |
| Heavy swing | `RButton` |
| Light swing | `LButton` |
| Block | `C` |
| Super | `F` |
| Air move | `X` |
| Sprint | `Shift` |
| Powered melee | `C` |

If your binds are different, open **Settings** and change them to match your Destiny 2 setup.

### Default shortcuts

| Module | Shortcut |
| --- | --- |
| Wish-Wall | `F3` |
| Warlock Skate | `F5` |
| Warlock Flat Skate | `F6` |
| Hunter Skate | `F7` |
| Hunter Flat Skate | `F8` |
| Rocket Fly | `B` |

### Common statuses

- **Ready**: the shortcut is active and can be used.
- **Waiting focus**: Destiny 2 is open, but another window is selected.
- **Game inactive**: Destiny 2 was not detected.
- **Paused**: automation was paused.
- **Conflict**: two shortcuts are using the same key.
- **Binding error**: one configured bind is not valid.
- **Running**: the app is running a macro.

### Wish-Wall

1. Go to the wish wall in Destiny 2.
2. Open the **Wish-Wall** menu in the app.
3. Choose the wish from the list.
4. Adjust **Sensitivity** if needed.
5. Choose **Speed** between `1` and `2`.
6. Make sure Destiny 2 is focused.
7. Press the configured shortcut.

### Rocket Fly

The **Rocket Fly** menu runs a quick sequence with click, rocket movement, and grenade.

Recommended rocket with velocity base 40 example: (Gjallahorn)

- Default shortcut: `B`
- Default detection: `10.0`
- Default grenade bind: `Q`

### Settings

Settings are saved in:

`%APPDATA%\D2Hub\settings.json`

### Common issues

- If the shortcut does not work, check if Destiny 2 is focused, the app is **Active**, and the module shows **Ready**.
- If **Waiting focus** appears, click Destiny 2 and try again.
- If **Game inactive** appears, open Destiny 2 or restart the app after the game is open.
- If the macro pressed the wrong key, fix the binds in **Settings** and click **Save**.
- If Wish-Wall misses symbols, adjust **Sensitivity**, **Speed**, and the initial crosshair position.
- If Rocket Fly is too strong or too weak, adjust **Detection** in the **Rocket Fly** menu.

## Important notes

- This is an unofficial tool.
- Use responsibly.
- The author is not responsible for anything that happens to your account.
- Any bugs found should be reported to Awoke on discord or using github bug tracer

## Credits

Made by **Awoke**

Discord: `awoke._.s`
