:earth_americas:
*[English](README-en.md) ∙ [Español](README-es.md)*

## Automatização de Edição de Vídeo Baseada em Áudio

*Note: Projeto ainda não finalizado*

O intuito deste trabalho é fornecer uma solução de edição de vídeo automatizada visando poupar o trabalho humano para edição de vídeos muito grandes e com certos padrões de edição. Para tal, foi utilizada da energia do áudio do vídeo para identificar os pontos chaves de edição, e fazer um corte do vídeo original em todos esses pontos chaves/de interesse e editar todos eles juntos em único arquivo.

## Sugestão de como importar o ambiente virtual

É altamente recomendável ao trabalhar com projetos python, utilizar de [ambientes virtuais](https://csguide.cs.princeton.edu/software/virtualenv), os ambientes virtuais Python ajudam a desacoplar e isolar versões do Python e pacotes pip associados. Isso permite que os usuários finais instalem e gerenciem seu próprio conjunto de pacotes que são independentes daqueles fornecidos pelo sistema. Os ambientes virtuais permitem que você tenha um ambiente estável, reproduzível e portátil. Você controla quais versões de pacotes são instaladas e quando são atualizadas.
Existem várias maneiras de se configurar um ambiente virtual em python, vou listar aqui alguns bons links que podem ajudar nessa configuração: [:link:](https://docs.python.org/3/library/venv.html), [:link:](https://realpython.com/lessons/creating-virtual-environment/), [:link:](https://towardsdatascience.com/virtual-environments-for-absolute-beginners-what-is-it-and-how-to-create-one-examples-a48da8982d4b), [:link:](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

Uma escolhido o método para criação do ambiente virtual, é só verificar uma maneira de criar o ambiente segundo o arquivo  `requirements.txt`. Também deixarei listado aqui algumas boas maneiras de se fazer isso: [:link:](https://developer.akamai.com/blog/2017/06/21/how-building-virtual-python-environment), [:link:](https://gist.github.com/luiscape/19d2d73a8c7b59411a2fb73a697f5ed4), [:link:](https://www.jetbrains.com/help/pycharm/managing-dependencies.html), [:link:](https://www.codegrepper.com/code-examples/python/conda+create+requirements.txt).

Minha recomendação é utilizar o [Anaconda](https://conda.io/projects/conda/en/latest/index.html) para realização da gerência de dependências e de ambientes virtualizados, de forma mais simples. E seguir as seguintes etapas:

- [Dowload do anaconda](https://www.anaconda.com/products/individual)
- Para criar o ambiente [abrir o anaconda prompt](https://stackoverflow.com/questions/47914980/how-to-access-anaconda-command-prompt-in-windows-10-64-bit/55545141#:~:text=Go%20with%20the%20mouse%20to,%22Anaconda%20Prompt%22%20will%20open.), digitar no terminal `pip install -r requirements.txt` ou se preferir usar a sintaxe conda `conda create --name <env_name> --file requirements.txt`
- É interessante verificar no [anaconda navigator](https://docs.anaconda.com/anaconda/navigator/getting-started/) se o ambiente foi criado da forma correta
- Uma vez criado o ambiente, deve-se verificar como trabalhar com esse ambiente dentro da IDE utilizada, seguem alguns links que exemplificam isso: [:link:](https://www.jetbrains.com/help/pycharm/conda-support-creating-conda-virtual-environment.html), [:link:](https://stackoverflow.com/questions/43351596/activating-anaconda-environment-in-vscode), [:link:](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/sublime/)
- Após seguir esse passo a passo, já é possível rodar o projeto em um ambiente adequado na IDE que for preferida.

## Licença





