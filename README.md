# Meu Rice do Sway

Este repositório contém minhas configurações e scripts pessoais do Sway (dotfiles).

## 📦 Conteúdo

*   **Gerenciador de Janelas:** [Sway](https://swaywm.org/)
*   **Barra:** [Waybar](https://github.com/Alexays/Waybar)
*   **Terminal:** [foot](https://codeberg.org/dnkl/foot)
*   **Lançador de Aplicativos:** [Wofi](https://hg.sr.ht/~scoopta/wofi)
*   **Notificações:** [Swaync](https://github.com/ErikReider/SwayNotificationCenter)
*   **Prompt (Terminal):** [Oh My Posh](https://ohmyposh.dev/)
*   **Informações do Sistema:** [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
*   **Controle do Mouse via Teclado:** [warpd](https://github.com/rvaiya/warpd)

## 🚀 Instalação

1.  Clone este repositório:
    ```bash
    git clone https://github.com/efzevios/Sway.git
    cd Sway
    ```

2.  Copie os arquivos de configuração para o seu diretório `~/.config`:
    ```bash
    cp -r .config/* ~/.config/
    ```

3.  Copie os arquivos `.bashrc` e `.profile` para a sua pasta de usuário (faça um backup dos seus originais primeiro!):
    ```bash
    cp .bashrc ~/.bashrc
    cp .profile ~/.profile
    ```

4.  Os scripts da pasta `Scripts/` podem ser copiados ou executados conforme sua necessidade.

## 🖼️ Papel de Parede

O papel de parede está localizado em `.config/background-d.jpg`. Ele será carregado automaticamente pela configuração do Sway, que espera encontrá-lo em `~/.config/background-d.jpg`.

## ⚙️ Scripts

Este repositório também inclui alguns scripts úteis na pasta `Scripts/` para configurar o Timeshift, áudio, SwayFX, KDE Connect, entre outras coisas.

---

*Nota: Lembre-se de revisar os arquivos de configuração para adaptá-los ao seu hardware específico, como nomes de monitores e resoluções no arquivo de configuração do Sway.*
