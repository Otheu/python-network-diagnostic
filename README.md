# Python Network Diagnostic

Projeto de aprendizado prático de Python e fundamentos de redes, com foco em diagnóstico de conectividade no Windows 11.

## Objetivo

Construir, passo a passo, uma ferramenta que execute testes de rede, interprete resultados e produza relatórios. O código será desenvolvido progressivamente durante os exercícios.

## Estrutura

- `main.py`: ponto de entrada do programa.
- `diagnostico.py`: módulo reservado para as funções de diagnóstico.
- `relatorios/`: pasta para relatórios locais (não versionar dados privados).
- `.gitignore`: evita publicar ambientes virtuais e arquivos locais.

## Executar

Instale Python 3 e execute no terminal:

```powershell
python main.py
```

## Roteiro

1. Executar `ping` com `subprocess.run()`.
2. Verificar o código de retorno do comando.
3. Permitir escolher o endereço IP.
4. Tratar erros e falhas de conectividade.
5. Produzir relatórios sem expor dados sensíveis.

> Uso educacional: execute testes apenas em sistemas e redes que você tem autorização para avaliar.
