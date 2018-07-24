**Autores:**
- Plácido Andrade
- Ikaro Costa

# Apresentação


As Diretrizes Curriculares Nacionais estabelecem os conteúdos necessários que devem
constar nos PPC’s do cursos ofertados pelas IES’s. Sendo assim, não cabe
uma análise se estes conteúdos devem ou não estar presentes da matriz curricular.
Entretanto vale um exame de quão extenso ou profundo eles foram utilizados
na formação profissional. Este projeto, visa a fazer um análise do ponto de vista
quantitativo e construir um aplicativo para realizar esta análise de PPC’s.

Este projeto é desenvolvido na [Universidade Federal do Cariri (UFCA)](http://www.ufca.edu.br)
sob apoio da Pró-Reitoria de Pesquisa, Inovação e Pós-graduação (PRPI).

# Índices

Define-se, então, dois índices com base nos pré-requisitos entre as disciplinas. São eles:
o índices de Complexidade e o Índice de Retenção.

Para maiores informações sobre os índices, consultar o arquivo disposto [neste link](/files/analiseppcs.pdf).

# Implementação

O aplicativo AnálisePPC foi desenvolvido em Python 3 e sua GUI (Guided User Interface) com auxílio das ferramentas
PyQt 4, QtDesigner e biblioteca matplotlib.

# Download

Os seguintes links possuem as versões disponíveis para download.

Essa é versão 1.0 do software AnálisePPC. A principal diferença entre as versões 0 e 1.0 é a verificação de possíveis erros quanto à inserção de disciplinas 
do PPC, além das correções de bugs.

- Linux: [Clique aqui.](https://drive.google.com/open?id=1RFXxFeQwc9VEuYRWibWyYnW12itnqqjX)
- Windows: [Clique aqui.](https://drive.google.com/file/d/1OseRyx3WOBoxkv2pDi16m3FD3x21IwwL/view?usp=sharing)

Os executáveis acimas foram produzidos pelo PyInstaller sob Fedora 24, para versão Linux, e Windows 10. A dependência de bibliotecas ainda é um caso a ser 
resolvido, logo a versão Windows continua com tamanho excessivo. 

***Atenção:*** Se deseja reportar algo de incomum no programa, por favor, entrar em contato com os autores.

# Instruções

## PPC Modelo

Para servir de modelo, apresento o PPC exemplo disponível [aqui](/files/matcomp.xml). Tal PPC pode ser aberto com os seguintes passos:

'''
Arquivo -> Abrir PPC -> Selecionar PPC exemplo ou outro
'''

Em seguida, para o cálculo dos índices siga:

'''
Calcular -> PPC1 (Caso esteja aberto na aba PPC1)
'''

Será uma mostrada uma nova janela com os resultados.

## Criando um novo PPC

Para criar um novo PPC, inicie com dados de carga horária complementar e de estágio supervisionado, assim como número de semestres requeridos para 
conclusão do curso de graduação.

**Atenção:** Apenas o nome não é um campo obrigatório na janela principal.

Em seguida, clique em "Adicionar Curso" e preencha as lacunas com os dados da disciplina.

**Atenção:** Todos os dados na janela de adicionar curso são obrigatórios. Para inserir os pré-requisitos siga as instruções dispostas na janela.

Após finalizada a inserção de disciplinas, pode-se proceder como:

'''
Calcular -> PPC1
'''

Caso as disciplinas tenham sido adicionadas na aba "PPC1", caso siga clique em "PPC2" no menu calcular.

## Comparando dois PPCs

Para proceder a comparação de dois PPCs, adicione ou abra cada PPC em uma aba distinta ("PPC1" e "PPC2") e prossiga para:

'''
Calcular -> Comparação
'''

Assim, uma janela de compação de índices será aberta.

# Contato

Para maiores informações entrar em contato com:

- Plácido Andrade. Email: _placido.andrade@ufca.edu.br_
- Ikaro Costa. Email: _ikaroruan@outlook.com_

# Agradecimento

A equipe de desenvolvimento do aplicativo agradece a todo o apoio recebido através da Pró-reitoria de
Pesquisa, Inovação e Pós-graduação (PRPI) da UFCA.
