# extensoes-vscode
lista de extensoes, comando para gerar e instalar
<p>
  salvar para arquivo:<br />
  <code>
    code --list-extensions | % { "$_" } > extensoes.txt
  </code>
</p>
<p>
  instalar do arquivo:<br />
  <code>
  cat .\extensoes.txt | { "code --install-extension $_" }
  </code>
</p>
