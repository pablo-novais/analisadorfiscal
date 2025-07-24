Analisador Fiscal de NF-e
Uma aplicação de desktop desenvolvida em Python para automatizar a análise de arquivos XML de Notas Fiscais Eletrônicas (NF-e). A ferramenta permite que usuários, mesmo sem conhecimento técnico aprofundado, processem lotes de notas fiscais, gerando relatórios detalhados em PDF e Excel.

Screenshot da Aplicação

![iamgem da tela principal da aplicacao](janela.PNG)

Com certeza! Apresentar um projeto no GitHub com uma documentação clara e profissional é uma habilidade essencial para um engenheiro de computação e valoriza imensamente seu portfólio.

Vamos criar uma documentação completa e bem estruturada para o seu projeto. Você pode usar este texto como o conteúdo do seu arquivo README.md no GitHub. O formato (Markdown) já está pronto para copiar e colar.

Passo 1: Crie o arquivo README.md
Na pasta do seu projeto, crie um novo arquivo de texto e nomeie-o exatamente como README.md.

Passo 2: Crie o arquivo requirements.txt
Este arquivo lista as bibliotecas que seu projeto precisa. É uma prática padrão e essencial. No seu terminal, na pasta do projeto, execute:

Bash

pip freeze > requirements.txt
Isso criará o arquivo automaticamente. Ele deve conter customtkinter, fpdf2, openpyxl, entre outras dependências.

Passo 3: Copie e Cole o Conteúdo Abaixo no seu README.md
Copie todo o texto a seguir e cole no seu arquivo README.md. Depois, leia e ajuste o que achar necessário.

Analisador Fiscal de NF-e
Uma aplicação de desktop desenvolvida em Python para automatizar a análise de arquivos XML de Notas Fiscais Eletrônicas (NF-e). A ferramenta permite que usuários, mesmo sem conhecimento técnico aprofundado, processem lotes de notas fiscais, gerando relatórios detalhados em PDF e Excel.

Screenshot da Aplicação
(Dica: Tire um print da tela principal do seu programa e salve na pasta do projeto como screenshot.png. O GitHub irá exibi-lo aqui automaticamente)

Funcionalidades Principais (Features)
Interface Gráfica Intuitiva: Desenvolvida com CustomTkinter para uma experiência de usuário moderna e amigável.

Análise em Lote: Processa múltiplos arquivos XML localizados em uma pasta de origem selecionada pelo usuário.

Classificação Automática: Separa as operações fiscais em Entradas e Saídas com base no primeiro dígito do CFOP.

Filtro por Período: Permite ao usuário definir um intervalo de datas ("De" e "Até") para analisar apenas as notas emitidas nesse período.

Geração de Relatórios Multi-formato:

PDF: Cria um relatório profissional com uma página de resumo (totais de entradas, saídas e impostos) e páginas de detalhes agrupadas por CFOP. Inclui rodapé com autoria e paginação.

Excel: Gera uma planilha .xlsx com abas separadas para Entradas e Saídas, facilitando análises posteriores.

Busca Rápida: Funcionalidade para localizar uma nota fiscal específica pelo seu número e exibir seus detalhes na tela.

Portabilidade: O projeto pode ser compilado em um único arquivo executável (.exe) com PyInstaller, permitindo o uso em qualquer máquina Windows sem a necessidade de instalar Python ou bibliotecas.

Tecnologias Utilizadas
Linguagem: Python 3

Interface Gráfica (GUI): CustomTkinter

Manipulação de XML: xml.etree.ElementTree (biblioteca padrão do Python)

Geração de PDF: fpdf2

Geração de Excel: openpyxl

Empacotamento: PyInstaller

Instalação e Uso
Existem duas formas de utilizar este projeto: como um usuário final (usando o .exe) ou como um desenvolvedor (executando o código-fonte).

Com certeza! Apresentar um projeto no GitHub com uma documentação clara e profissional é uma habilidade essencial para um engenheiro de computação e valoriza imensamente seu portfólio.

Vamos criar uma documentação completa e bem estruturada para o seu projeto. Você pode usar este texto como o conteúdo do seu arquivo README.md no GitHub. O formato (Markdown) já está pronto para copiar e colar.

Passo 1: Crie o arquivo README.md
Na pasta do seu projeto, crie um novo arquivo de texto e nomeie-o exatamente como README.md.

Passo 2: Crie o arquivo requirements.txt
Este arquivo lista as bibliotecas que seu projeto precisa. É uma prática padrão e essencial. No seu terminal, na pasta do projeto, execute:

Bash

pip freeze > requirements.txt
Isso criará o arquivo automaticamente. Ele deve conter customtkinter, fpdf2, openpyxl, entre outras dependências.

Passo 3: Copie e Cole o Conteúdo Abaixo no seu README.md
Copie todo o texto a seguir e cole no seu arquivo README.md. Depois, leia e ajuste o que achar necessário.

Analisador Fiscal de NF-e
Uma aplicação de desktop desenvolvida em Python para automatizar a análise de arquivos XML de Notas Fiscais Eletrônicas (NF-e). A ferramenta permite que usuários, mesmo sem conhecimento técnico aprofundado, processem lotes de notas fiscais, gerando relatórios detalhados em PDF e Excel.

Screenshot da Aplicação
(Dica: Tire um print da tela principal do seu programa e salve na pasta do projeto como screenshot.png. O GitHub irá exibi-lo aqui automaticamente)

Funcionalidades Principais (Features)
Interface Gráfica Intuitiva: Desenvolvida com CustomTkinter para uma experiência de usuário moderna e amigável.

Análise em Lote: Processa múltiplos arquivos XML localizados em uma pasta de origem selecionada pelo usuário.

Classificação Automática: Separa as operações fiscais em Entradas e Saídas com base no primeiro dígito do CFOP.

Filtro por Período: Permite ao usuário definir um intervalo de datas ("De" e "Até") para analisar apenas as notas emitidas nesse período.

Geração de Relatórios Multi-formato:

PDF: Cria um relatório profissional com uma página de resumo (totais de entradas, saídas e impostos) e páginas de detalhes agrupadas por CFOP. Inclui rodapé com autoria e paginação.

Excel: Gera uma planilha .xlsx com abas separadas para Entradas e Saídas, facilitando análises posteriores.

Busca Rápida: Funcionalidade para localizar uma nota fiscal específica pelo seu número e exibir seus detalhes na tela.

Portabilidade: O projeto pode ser compilado em um único arquivo executável (.exe) com PyInstaller, permitindo o uso em qualquer máquina Windows sem a necessidade de instalar Python ou bibliotecas.

Tecnologias Utilizadas
Linguagem: Python 3

Interface Gráfica (GUI): CustomTkinter

Manipulação de XML: xml.etree.ElementTree (biblioteca padrão do Python)

Geração de PDF: fpdf2

Geração de Excel: openpyxl

Empacotamento: PyInstaller

Instalação e Uso
Existem duas formas de utilizar este projeto: como um usuário final (usando o .exe) ou como um desenvolvedor (executando o código-fonte).

Para Usuários Finais
Vá para a seção Releases deste repositório.

Baixe a versão mais recente do Analisador.Fiscal.v2.exe.

Execute o arquivo. Não é necessária nenhuma instalação.

Autor
Pablo Novais
github.com/pablo-novais
linkedin.com/in/pablonovaisramos
