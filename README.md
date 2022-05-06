# Visual-Studio-Code

### Fonte
Para ter uma fonte mais personalizada e com todos aqueles símbolos especiais quando combinamos alguns caracteres, basta seguir alguns passos:

Faça download da fonte em https://github.com/tonsky/FiraCode.

Instale as fontes da pasta TTF (selecione todas e com o botão direito do mouse > Install)

![image](https://user-images.githubusercontent.com/7897250/167137707-1227d6d8-e919-4fdc-8c64-2483eee49ac4.png)

No VsCode precisamos abrir o settings.json, para isso pressione ctrl+, (Windows) ou cmd + , (Mac)

Ao abrir as Options, pesquise por settings.json, em seguida click em Edit in settings.json.

![image](https://user-images.githubusercontent.com/7897250/167137762-851cf144-4df4-47fa-b647-26f533f81362.png)

Adicione a seguinte configuração

configurações:
```
 "editor.fontFamily": "Fira Code",
 "editor.fontSize": 12,
 "editor.fontLigatures": true
```
Reinicie o VsCode e divirta-se

Veja como fica o antes e depois

![image](https://user-images.githubusercontent.com/7897250/167137950-ac331b8a-9acb-4d85-860e-404db1991fb5.png)

### Extensões
Extensões são formas de adicionar ainda mais funcionalidades ao seu Visual Studio Code.

Vamos citar 2 aqui para você:

#### Material Icon Theme
O Material Icon Theme é uma extensão que permite a customização dos ícones das pastas por extensões de arquivos, por exemplo, com ele conseguimos customizar um ícone para arquivos Typescript, outro para Javascript, outro para HTML e assim por diante. 

**Como instalar?** ⬇️
![image](https://user-images.githubusercontent.com/7897250/167139431-0308f7c2-4c56-40a6-a5f4-67985368973e.png)

**Configurações**

Para finalizar, vamos adicionar algumas configurações no Visual Studio Code. Para isso, basta pressionar Ctrl + Shift + P e escolher a opção Open Settings (JSON). Na janela que foi aberta, adicione as configurações abaixo:

```
É preciso tomar alguns cuidados ao realizar essas alterações. Verifique se a configuração adicionada já não existe no arquivo. Se sim, apenas atualize o valor. 

Verifique também se a todas as linhas de configuração exceto a última terminam com vírgula, para não gerar erro. 

Por fim, caso queira substituir completamente a sua configuração pela abaixo, envolva com chaves {} todo o código disponibilizado.
```
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "Dracula",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 12,
  "editor.fontLigatures": true,
  "explorer.compactFolders": false,
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "extensions.ignoreRecommendations": true,

  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "never",

  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": false,

  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  
  "emmet.syntaxProfiles": { "javascript": "jsx" },
  "emmet.includeLanguages": { "javascript": "javascriptreact" },

  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
```
### Opcional - Configurações adicionais do VS Code
Se você já configurou todo o ambiente seguido os passos anteriores e quer deixar o Visual Studio Code com mais funcionalidades

#### Extensões
Você pode instalar as seguintes extensões a partir do menu de extensões do próprio VS Code:

- **[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)**: Essa extensão faz a correção ortográfica no nosso código, funcionando melhor com camelcase (por padrão, corrige apenas o inglês). Essa extensão é bastante útil mas é totalmente opcional;
- **[Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese)**: É um dicionário de português para que a extensão **Code Spell Checker** consiga fazer também a correção ortográfica em Português;
- **[Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)**: Essa extensão reconhece cores CSS escritas em qualquer lugar do nosso código. Por padrão reconhece apenas cores em hexadecimal mas você pode configurar para reconhecer cores no formato de palavras como `"red"` ou `"yellow"`. É uma extensão bastante útil, já que reconhece as cores diretamente no código;
- [**CSS Modules**](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules): Essa é uma extensão que fornece o autocomplete para CSS Modules. Recomendamos o uso dela já que vai te ajudar com o autocomplete;
- [**Tabnine**](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode): O Tabnine é uma extensão que usa de inteligência artificial para identificar o contexto do código e fornecer o autocomplete. Suporta diversas linguagens incluindo JavaScript e TypeScript. Existe uma versão paga mas também é possível usar a versão gratuita da extensão.
Seu uso é totalmente opcional;
- [**vscode-styled-components**](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components): Essa extensão fornece o syntax highlighting e intelliSense para a biblioteca [styled-components](https://styled-components.com/). Se você for utilizar essa biblioteca, o uso da extensão é bastante recomendado.
