# Calculadora Python + Flet para Desktop 💻
[![Download](https://img.shields.io/badge/Download-Latest%20Version-blue)](https://github.com/piedro404/calculator_flet_python/blob/main/dist/Calculadora.exe)

Uma calculadora para Desktop feito para ganhar Experiência no Framework Flet para futuros projetos, realizado com base [Tutorial](https://youtu.be/rcMuTUpqUsU?si=ybf6-XA4JzLcJ5Tt) do canal [Programador Aventureiro](https://www.youtube.com/@ProgramadorAventureiro). 

<img width="179" alt="Calculadora Relpica do IPhone com Python + Flet" src="https://github.com/piedro404/calculator_flet_python/assets/88720549/3c84f98a-80af-47ec-a2fd-8bafe9933396">

# Principais Tecnologias Utilizadas 🌐
- Flet: Framework utilizado para o desenvolvimento de interface GUI em diversas Plataformas como Android, IOS, Desktop, WEB.
- Python: Linguagem de programação principal.
- Outras Bibliotecas: O resto das bibliotecas pode ser encontradas no requirements.txt

```Bash
  pip install -r requirements.txt
```

# Documentação 📖
Para mais aprofundamento nas funcionalidades, estrutura e recursos, recomendo fortemente dar uma olhada na [documentação](https://flet.dev/docs/) do Flet.

```Bash
  pip install flet
```

<img width="930" alt="Documentação" src="https://github.com/piedro404/calculator_flet_python/assets/88720549/3e3e5d6c-5177-4770-9562-e149c20fc00c">

## Dicas 🧩
### Builder 🧑‍💻
Para gerar o executável, além do Flet, será necessário o Pyinstaller, mas não se preocupe, já que o próprio Flet cuidara do builder. 
```Bash
  pip install pyinstaller
```
Você também pode usar o comando abaixo para obter mais informações.
```Bash
  flet pack --help
```

Exemplo do Comando Pack para Buildar o Projeto:
```Bash
  flet pack FILE_PROJECT.py --icon DIRETORIO_ICONE.ico --name NOME_PROJETO --company-name COMPANY --file-version VERSION [x.x.x.x] --file-description DESCRIPTION --product-name PRODUCT_NAME
```

### Ícones no Builder e na Window 🖼️
Para pôr um Ícone, será necessário por no formato (.ico). 
Consulte essa [Discussão](https://stackoverflow.com/questions/73540154/how-to-change-the-default-loading-icon-in-a-python-flet-app) criada no site Stack Overflow para mais Detalhes.
Caso já tenha o PNG e não saiba como converter, use esse site para converter [Convertio](https://convertio.co/pt/png-ico/).

<img width="930" alt="Convertio" src="https://github.com/piedro404/calculator_flet_python/assets/88720549/e1faefc0-459b-471e-b353-bf8f9a470c22">

### Ambiente Virtualizado 🖥️
Para organização e facilitar no Builder do projeto, sugiro criar um ambiente virtualizado. Para isso, basta usar o comando abaixo:
```Bash
  python -m venv .venv
```

E para usar o ambiente, basta ativá-lo usando:
```Bash
  .venv\Scripts\activate
```

# Como Executar o Projeto 🛠️
1. Clone este repositório:
   
   ```bash
   git clone https://github.com/piedro404/calculator_flet_python.git
   ```
   
2. Instale as dependências: 

   ```bash
   pip install -r requirements.txt
   ```
   
3. Execute a aplicação: 

   ```bash
   flet run app.py
   ```

# Sobre 📒
Obrigado a todos, desejo ótimos estudos, caso queira, entre em contato em pedro.henrique.martins404@gmail.com;
