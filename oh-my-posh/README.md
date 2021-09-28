# Usage   
[documentation](https://ohmyposh.dev/)
## WSL
###  Ubuntu  
Move `yc.omp.json` to `HOME` folder, then add the following to `~/.bashrc`    
    ```
    eval "$(oh-my-posh-wsl --init --shell bash --config ~/yc.omp.json)"
    ```
### powershell
Move `yc.omp.json` to `HOME` folder, then add the following to `$PROFILE`    
    ```
    oh-my-posh --init --shell pwsh --config ~/yc.omp.json | Invoke-Expression
    ```  

If there are some box symbols in prompt, it means that the icons can be be displayed correctly. Then we have two options([issue#90](https://github.com/JanDeDobbeleer/oh-my-posh/issues/89)):  
- install [nerd font](https://www.nerdfonts.com/)  
- override the icons with icons which are availables in Cascadia Code  
