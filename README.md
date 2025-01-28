# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

git clone  https://github.com/mtzirkel/lazyvim.git ~/.config/nvim

-------------------------------------------------------------------------------------------------------------------------------


Step 1: Download a Nerd Font
Visit the Nerd Fonts Releases Page:
Go to the Nerd Fonts GitHub Releases page and choose the font you want to install. You can download the .zip file for the font of your choice.
Step 2: Install the Font
Unzip the Font:
After downloading, unzip the file. You can do this via the terminal:

bash
unzip path/to/your/downloaded/font.zip -d ~/Downloads/nerd-fonts  
Copy the Font to the Fonts Directory:
Copy the unzipped font files to your local fonts directory:

bash
mkdir -p ~/.local/share/fonts  
cp ~/Downloads/nerd-fonts/*.ttf ~/.local/share/fonts/  
Rebuild the Font Cache:
Run the following command to rebuild the font cache:

bash
fc-cache -fv  
Step 3: Configure Your Terminal
Set Your Terminal to Use the Nerd Font:
Open your terminal settings and change the font to the Nerd Font you installed. This step varies depending on the terminal emulator you are using (e.g., GNOME Terminal, Alacritty, etc.).
Step 4: Verify Installation
Check in Neovim:
Open Neovim and check if the Nerd Font is being used correctly. You can test it by using icons or symbols that are part of the Nerd Font set.
