# Meu Rice do Sway

Este repositório contém minhas configurações e scripts pessoais do Sway (dotfiles).

## 📦 Conteúdo Atual

*   **Gerenciador de Janelas:** [Sway](https://swaywm.org/)
*   **Barra:** [Waybar](https://github.com/Alexays/Waybar)
*   **Terminal:** [foot](https://codeberg.org/dnkl/foot)
*   **Menu / Lançador de Aplicativos:** dms *(substituiu o Wofi)*
*   **Prompt (Terminal):** [Oh My Posh](https://ohmyposh.dev/)
*   **Informações do Sistema:** [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
*   **Controle do Mouse via Teclado:** [warpd](https://github.com/rvaiya/warpd)

*(Componentes como Wofi e Swaync não são mais utilizados no setup atual. Seus arquivos foram mantidos na pasta `.config/antigos/` caso queira acessá-los.)*

## 🚀 Instalação

1.  Clone este repositório:
    ```bash
    git clone https://github.com/efzevios/Sway.git
    cd Sway
    ```

2.  Copie os arquivos de configuração atuais para o seu diretório `~/.config` (ignorando a pasta de antigos, se quiser):
    ```bash
    cp -r .config/* ~/.config/
    ```

3.  Copie os arquivos `.bashrc` e `.profile` para a sua pasta de usuário (faça um backup dos seus originais primeiro!):
    ```bash
    cp .bashrc ~/.bashrc
    cp .profile ~/.profile
    ```

## 🖼️ Papel de Parede

O papel de parede está localizado em `.config/background-d.jpg`. Ele será carregado automaticamente pela configuração do Sway, que espera encontrá-lo em `~/.config/background-d.jpg`.

## ⚙️ Scripts

Os scripts do sistema foram reorganizados para facilitar o uso:

*   **`Scripts/atuais/`**: Contém os scripts em uso hoje no setup (como configurações do dms, áudio, Timeshift, SwayFX, etc).
*   **`Scripts/antigos/`**: Contém scripts antigos, guardados apenas como histórico e referência.

---

*Nota: Lembre-se de revisar os arquivos de configuração para adaptá-los ao seu hardware específico, como nomes de monitores e resoluções no arquivo de configuração do Sway.*
