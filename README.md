# **Header 42SP**

42 (São Paulo)

### **Descrição**

Cabeçalho padrão 42 para o Vim.

### **Configuração no UNIX**

Copie o arquivo `stdheader.vim` para `~/.vim/plugin`, ou use o seu gerenciador de plugins favorito. Em seguida, defina as variáveis de usuário e e-mail conforme explicado abaixo.

#### Opção 1: exporte USER e MAIL no arquivo de configuração do seu shell

Adicione em `~/.zshrc` o seguinte:

```zsh
export USER="seu_nick_da_intra"
export MAIL="seu_nick_da_intra@student.42sp.org.br"
```

### **Uso**

No modo **NORMAL**, você pode usar `:Stdheader` ou simplesmente pressionar o atalho <kbd>F1</kbd>.

Ou, você pode executar o script do repositório:

```zsh
./set_header.sh`
```
