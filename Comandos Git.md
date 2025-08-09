**Relacionados:** [[Terminal]]
**Date:** 31-07-2025
**Tópicos:** #git

### Git

- `git remote add origin URL`  
    Define o repositório remoto (linkar local com online).
    
- `git remote set-url origin URL`  
    Muda a URL do repositório remoto.
    
- `git push --set-upstream origin branch`  
    Envia a branch local para o remoto e configura tracking.
    
- `git branch`  
    Lista branches locais.
    
- `git branch -r`  
    Lista branches remotas.
    
- `git branch -a`  
    Lista todas as branches (locais + remotas).
    
- `git checkout branch`  
    Troca para a branch especificada.
    
- `git checkout -b branch`  
    Cria e troca para a nova branch.
    
- `git merge branch`  
    Junta a branch especificada na branch atual.
    
- `git pull`  
    Atualiza a branch local com mudanças do remoto.
    
- `git branch --set-upstream-to=origin/branch branch`  
    Define o tracking da branch local com a remota.
    
- `git pull origin branch --allow-unrelated-histories`  
    Puxa e força merge mesmo sem histórico comum.
    
- `git config pull.rebase true|false`  
    Configura se o `git pull` faz rebase (true) ou merge (false).
    
- `git status -sb`  
    Mostra status resumido e branch atual.
    
- `git branch --show-current`  
    Mostra só a branch atual.
    

---

### Terminal (Termux/Linux)

- `mv arquivo pasta/`  
    Move arquivo ou pasta para outro diretório.
    
- `mv arquivo1 pasta1 arquivo2 pasta2 destino/`  
    Move vários arquivos/pastas para destino.
    
- `rm -rf pasta`  
    Apaga pasta e tudo dentro (perigoso!).
    
- `rmdir pasta`  
    Apaga pasta **vazia**.
    
- `rm arquivo`  
    Apaga arquivo.
    
- `pkg install less`  
    Instala o pager `less` no Termux.
    
- `git branch -r --no-pager`  
    Lista branches remotas sem usar pager.
    

---

### Prompt com cor (no `~/.bashrc`)

```bash
parse_git_branch() {
  git branch 2>/dev/null | grep '*' | sed 's/* //'
}

export PS1='\[\e[32m\]\w\[\e[m\]$( 
  branch=$(parse_git_branch); 
  if [ -n "$branch" ]; then 
    echo " \[\e[33m\]$branch"; 
  fi
)\[\e[m\] $ '
```

- Mostra o caminho em verde.
- Mostra a branch Git em amarelo se estiver dentro de um repo.
