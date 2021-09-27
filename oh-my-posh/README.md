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
