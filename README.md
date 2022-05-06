# Visual-Studio-Code

**Fonte**
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
