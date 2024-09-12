# **Explicação de Modelos de Aprendizado de Máquina: SHAP, LIME e Anchors**

Este repositório contém exemplos práticos de explicação de modelos de aprendizado de máquina usando três técnicas populares: **SHAP (SHapley Additive Explanations)**, **LIME (Local Interpretable Model-Agnostic Explanations)** e **Anchors (Alibi)**.

## **Conteúdo do Repositório**

```bash
.
├── ALIBI(ANCHOR) Sale_classification.ipynb          # Exemplo de uso do Anchors para classificação de vendas
├── LIME - basic usage, two class case.ipynb         # Exemplo básico de LIME para um caso de duas classes
├── readme.md                                        # Este arquivo README
├── requirements.txt                                 # Dependências necessárias para o projeto
└── SHAP Emotion classification multiclass example.ipynb # Exemplo de SHAP para classificação de emoções (multiclasse)
```

### **Descrição dos Arquivos:**

- **ALIBI(ANCHOR) Sale_classification.ipynb**: Contém um exemplo de aplicação do método Anchors (Alibi) para explicar um modelo de classificação de vendas. Demonstra como identificar "regras de ancoragem" que justificam as previsões do modelo.

- **LIME - basic usage, two class case.ipynb**: Fornece um exemplo básico de uso do LIME para explicar as previsões de um modelo de classificação binária. Mostra como o LIME perturba os dados de entrada para gerar explicações locais.

- **SHAP Emotion classification multiclass example.ipynb**: Demonstra como o SHAP pode ser usado para explicar um modelo de classificação de emoções em um cenário de múltiplas classes. Utiliza valores de Shapley para avaliar a contribuição de cada característica para as previsões.

- **requirements.txt**: Lista as dependências necessárias para executar os notebooks. Certifique-se de instalar todas as bibliotecas antes de rodar os exemplos.

## **Como Usar este Repositório**

1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/LogicExplainML-LEML.git
   cd LogicExplainML-LEML/LIME-SHAP-ANCHORS
   ```

2. **Instale as Dependências:**
   Certifique-se de ter o Python 3.x instalado e execute o seguinte comando para instalar as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute os Notebooks:**
   Utilize o Jupyter Notebook ou qualquer outra ferramenta compatível para abrir e executar os notebooks `.ipynb`.

## **Pré-requisitos**

- Python 3.x
- Jupyter Notebook
- Bibliotecas especificadas no `requirements.txt`
Recomendo utilizar o Google Colab

## **Dependências**

Certifique-se de que as seguintes bibliotecas estejam instaladas:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `shap`
- `lime`
- `alibi`

Para instalar todas as dependências de uma vez, execute:
```bash
pip install -r requirements.txt
```

## **Referências**

- [SHAP Documentation](https://shap.readthedocs.io/)
- [LIME Documentation](https://marcotcr.github.io/lime/)
- [Alibi Documentation (Anchors)](https://docs.seldon.io/projects/alibi/en/stable/)

## **Contribuição**

Sinta-se à vontade para contribuir com melhorias ou novos exemplos. Para isso, faça um fork do repositório, crie uma nova branch para suas alterações, e envie um pull request.

## **Licença**

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

