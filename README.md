Vamos elaborar um site para apresentar os integrantes de uma equipe. Os dados podem ser fictícios ou não.

Exemplos: uma equipe de basquete, os personangens de algum filme, uma equipe de uma empresa.

Para isso, elabore uma página principal, cujo arquivo terá o nome "index.html". Esse arquivo deve ficar na pasta "site".

Nesta página deve constar uma lista não ordenada, onde cada item da lista terá a imagem e o nome de cada um dos participantes da equipe.

A imagem de cada membro da equipe deve ser um link para a página pessoal de cada um.

Elabore também uma página pessoal para cada um dos membros da equipe. Estas páginas deverão ficar na pasta "equipe". 

Nessa página deve constar uma lista ordenada com as empresas onde já trabalhou (pelo menos três).

Também deve ter uma lista ordenada com as habilidades/especialidades que possui.

Deve existir um link para retornar para a página principal (index.html).

Use a seguinte estrutura de pastas (diretórios):

Crie uma pasta "site", dentro dela crie duas pastas "equipe" e "imagens".

O arquivo index.html deve ficar na pasta "site".

Os arquivos html de cada participante da equipe devem ficar na pasta "equipe".

As imagens utilizadas nesse site devem ficar na pasta "imagens".

Utilize endereços relativos para os atributos href (da tag <a> ) e src da tag <img>. Lembre que ".." (- dois pontos - representa o diretório (ou pasta) acima da pasta que está tomando como referência.

Por exemplo, no arquivo "pessoa1.html" queremos inserir a imagem que está no arquivo "foto1.jpg". Como o arquivo "pessoa1.html" está dentro da pasta "equipe", o código ficaria

<img src="../imagens/foto1.jpg">
Para inserir essa mesma imagem no arquivo "index.html"

<img src="imagens/foto1.jpg">
outra forma que produz o mesmo resultado
<img src="./imagens/foto1.jpg">
(lembrando que um ponto representa a pasta que contém o arquivo onde está este código)


