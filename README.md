# test-htt-configs
Este repo é uma forma de armazenar templates para tags custom,
e os seus ficheiros de config.

### Como funciona o fetching das tags e configs?
Através de um __GET__ request ao ficheiro neste ou um repo com este tipo de ficheiros,
o programa [HTT](https://github.com/TomascpMarques/Html-Template-Transpiler), 
irá buscar o conteudo no dominio ```raw``` do github.com. 
O programa irá procurar pelo manifesto do _template_ e irá buscar o conteudo encontrado nesse template
