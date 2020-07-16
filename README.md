# fuzzy
Problema da gorjeta
O problema consiste em definir o valor da gorjeta em um restaurante com base na qualidade do serviço e da comida.

Entrada (antecedentes):
  Qualidade da Comida

  Universo (intervalo de valores nítidos/crisp): 0 a 10

  Conjunto difuso (valores difusos): péssima, comível, deliciosa

  Qualidade do Serviço

  Universo (intervalo de valores nítidos/crisp): 0 a 10

  Conjunto difuso (valores difusos): ruim, aceitável, excelente

# Saída (consequentes):
  Gorjeta

  Universo (valores nítidos/crisp): 0 a 25%

  Conjunto difuso (valores difusos): baixa, média, alta

# Regras de Decisão
  SE o serviço foi excelente OU a comida estava deliciosa ENTÃO a gorjeta deve ser alta

  SE o serviço foi aceitável ENTÃO a gorjeta deve ser média

  SE o serviço foi ruim E a comida estava péssima ENTÃO a gorjeta deve ser baixa

# install
pip install scikit-fuzzy
