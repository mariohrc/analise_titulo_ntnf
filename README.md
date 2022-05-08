## MarioCesa_Turma780_AnalisePrefixado

Construção de uma calculadora de renda fixa em Python - NTN-F
Formato de envio: arquivo .ipynb (Jupyter Notebook) conforme instruções a seguir.

Pode construir quantos métodos/classes/funções adicionais desejarem;
Pode utilizar bibliotecas abertas;
O arquivo deve conter as funções solicitadas e os cenários de teste (pelo menos um teste para cada função/método).
Comente as funções e o que mais achar necessário no código;
Grupos de até 4 pessoas.
Exemplo de definição da função com docstring detalhando os parâmetros:

def calcula_soma(a, b):
''' Calcula a soma de dois números decimais
    a: float
    b: float
    '''
    return a + b
Exemplo de teste da função com a definição dos parâmetros e chamada da função:

a = 1.3
b = 10.07
resultado = calcula_soma(a, b):
print(f'Resultado: {resultado}')

A nota da avaliação considerará apenas o resultado das funções desejadas (existência de bugs, bom funcionamento, etc);

Na avaliação qualitativa, faremos comentários de melhorias na estrutura do código (para fins de evolução de aprendizado, e não para reduzir nota).

Funções/métodos mínimos de entrega:

calcula_prazo(dt_ini, dt_fim, feriados, convencao)
Retorna: prazo anualizado (float)
convencao: 'DU/252' ou 'DC/360'

constroi_fluxo(dt_fim, frequencia)
Retorna: Lista de datas dos fluxos (list datetime.date)


calcula_pu(VF, prazo_anual, taxa_anual)
Retorna pu (float)

calcula_taxa_anual(PU, prazo_anual, valor_base=100)
Retorna: taxa_anual (float)


calcula_pu_ntnf(dt_venc, dt_base, tir) *
Retorna: pu (float)
Imprime tabela com o cashflow (Data do fluxo, VF, DU, Fator de desconto, PU)
