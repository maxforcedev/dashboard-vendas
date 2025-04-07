# 📞 Dashboard Interativo de Vendas - Call Center

Este projeto é um **dashboard interativo** construído com **Dash + Plotly + Python**, focado na análise de desempenho de vendas em um ambiente de call center. Ele apresenta KPIs, gráficos dinâmicos, seleção por equipe e mês, além de visual clean com troca de tema (claro/escuro).


---
![image](https://github.com/user-attachments/assets/1841f37f-44bf-4028-a43c-3a8f9c970ac7)


## 🚀 Funcionalidades

- 📊 Gráficos interativos com filtros de mês e equipe
- 🧑‍💼 Indicadores de melhor vendedor e equipe destaque
- 📈 Análise de chamadas por dia e mês
- 🎯 Visualização de campanhas de marketing mais eficazes
- 🌗 Alternância entre tema claro e escuro
- 🌐 Pronto para deploy com suporte a produção

---

## 🛠️ Tecnologias Utilizadas

- Python
- Dash
- Plotly
- Pandas
- Dash Bootstrap Components
- Dash Bootstrap Templates

---

## 📂 Organização do Projeto

```
📁 project-root/
├── app.py                # Código principal do dashboard
├── dataset.csv           # Base de dados utilizada
├── requirements.txt      # Dependências do projeto

```

---

## ▶️ Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/maxforcedev/dashboard-vendas.git
cd seurepositorio

# Crie o ambiente virtual (opcional)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute o app
python app.py
```

Acesse em: `http://127.0.0.1:8050`

---

## ☁️ Deploy

O projeto está configurado para deploy automático via [Render](https://render.com/), bastando adicionar:

- `requirements.txt`
- `app.py` com `host='0.0.0.0'` e `port=int(os.environ.get("PORT", 8050))`


---

## 📸 Screenshots

| Tema Claro                          | Tema Escuro                          |
|------------------------------------|--------------------------------------|
| ![image](https://github.com/user-attachments/assets/d9afd7f4-8958-44b5-89f0-3e55054fb159)         | ![image](https://github.com/user-attachments/assets/1e672c14-e968-43e0-ae94-8f742298929b) |

---

## 👨‍💻 Autor

**Luis Felipe C V Silva**  
🔗 [GitHub](https://github.com/maxforcedev)  
🔗 [LinkedIn](https://linkedin.com/in/maxforcedev)

---

## 📌 Status

✔️ Projeto finalizado e em produção  
🚧 Melhorias visuais e funcionalidades futuras em planejamento

---

## 🏁 Licença

MIT - sinta-se livre para usar, estudar e modificar.
