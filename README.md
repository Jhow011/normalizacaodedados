
# 🧩 Normalização de Banco de Dados — Projeto Prático

## 📊 Antes da Normalização

O banco de dados possuía uma **única tabela (`pedidos`)** que concentrava informações de **clientes, produtos e pedidos**.  
Essa estrutura gerava **redundância**, **inconsistência** e dificultava a **manutenção dos dados**.

### 🔹 Problemas identificados:
- Dados de clientes e produtos se repetiam em vários registros  
- Dificuldade para atualizar informações (como telefone ou endereço)  
- Falta de integridade referencial  
- Violações da 1ª e 2ª Forma Normal (1FN e 2FN)

🖼️ **Modelo antes da normalização:**  
*(adicione aqui a imagem do modelo não normalizado)*  
```bash
![](.)

