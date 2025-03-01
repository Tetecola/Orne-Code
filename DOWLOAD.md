### Aqui está um passo a passo rápido para fazer o download do **Orne Code** no **VS Code**  

Abra o terminal do VS Code

Faça o dowload da Extensão através do seguinte código

````powershell
Invoke-WebRequest -Uri "https://github.com/Tetecola/Orne-Code/releases/download/v2.1.0/orne-code-2.1.0.vsix" -OutFile "orne-code.vsix"
````
Em seguida instale a extensão
````powershell
code --install-extension orne-code.vsix
````

Pronto, agora é somente aproveitar o que o Orne Code tem de melhor a oferecer
