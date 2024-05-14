# Aprendendo ABAP

# Trasacoes
 - SE38 - ambiente de desenvolvimento
 - SE80 - criar pacote
 - SE10 - consultar resquestes

# Variaveis

```
DATA ld_raio(12) TYPE p DECIMALS 2;
```

- DATA: Esta palavra-chave é usada para declarar variáveis em ABAP.
- ld_raio é o nome da variável.
- (12) especifica a longura total da variável, ou seja, o número total de posições (dígitos) que a variável pode armazenar, incluindo os dígitos à esquerda e à direita do ponto decimal.
- TYPE é usado para especificar o tipo de dado da variável.
- p indica que a variável é do tipo packed number (número compactado ou número decimal). Esse tipo é usado para representar números decimais com precisão fixa.
-  DECIMALS 2 especifica o número de casas decimais que a variável terá. No caso, 2 casas decimais.

### Tipos de variaveis
- C (Character): Utilizado para armazenar cadeias de caracteres de comprimento fixo.
- N (Numeric Text): Usado para armazenar números em forma de texto.
- D (Date): Armazena datas no formato AAAAMMDD.
- T (Time): Armazena horários no formato HHMMSS.
- I (Integer): Utilizado para armazenar números inteiros.
- F (Floating Point): Usado para armazenar números de ponto flutuante.
- P (Packed Number): Utilizado para armazenar números decimais compactados.
- X (Hexadecimal): Usado para armazenar dados binários em formato hexadecimal.
- String: Utilizado para armazenar cadeias de caracteres de comprimento variável.
- XString: Usado para armazenar dados binários de comprimento variável.
  
# Constantes



# Tipos de Dados Estruturados
Tipos de dados estruturados são compostos de vários campos, cada um dos quais pode ser de um tipo diferente:

- Estruturas: Coleções de campos que podem ser de diferentes tipos de dados.
- Tabelas Internas: Semelhantes a arrays ou listas em outras linguagens, são usadas para armazenar conjuntos de registros.
  
# Tipos de Dados de Referência
Os tipos de dados de referência são usados para apontar para outros objetos e dados:

- Ref to Data: Aponta para qualquer tipo de dados dinâmico.
- Ref to Object: Aponta para objetos instanciados.
- 
# Tipos de Dados Definidos pelo Usuário
Os desenvolvedores podem definir seus próprios tipos de dados com base nos tipos básicos, estruturas e tabelas internas:

- Tipos definidos pelo usuário (Types): Permitem definir tipos complexos personalizados.
- Constantes (Constants): Valores imutáveis definidos pelo usuário.
- Domínios: Definem o intervalo de valores válidos para um campo de dados.
- Elementos de Dados: Definem a semântica de um campo de dados e são baseados em domínios.
  
# Variáveis de Campo de Símbolos
Campos de símbolos são uma forma especial de variáveis que permitem acesso dinâmico a campos e estruturas:

- Field-Symbols: Permitem a referência indireta a campos de dados.
  
# Parâmetros e Seleções
Utilizados em programas ABAP para entrada de dados:

- Parâmetros: Usados para entrada de dados simples.
- Seleções: Utilizadas para definir intervalos ou conjuntos de valores para a seleção de dados.
