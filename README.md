# 🌞 **Solar Panel Detection - 2TDSPA**

### Melissa Barbosa de Souza - 552535  
### Alissa Silva Cezero - 553954  
### Nicolas Paiffer do Carmo - 554145  

---

## 💡 Sobre o Projeto

Este projeto integra **visão computacional e sustentabilidade** para melhorar a manutenção de placas solares usadas no carregamento de bicicletas elétricas.

A ideia é simples e inteligente: bicicletas elétricas distribuídas em locais estratégicos da cidade (estações de metrô, avenidas, etc) são carregadas por energia solar. Para manter esse sistema funcionando perfeitamente, criamos um modelo que **detecta problemas nas placas solares**, otimizando o processo de manutenção.

---

## 🔍 O que o modelo faz

Nosso modelo de visão computacional classifica imagens de placas solares em **cinco categorias**:

- ✅ **Clean** — Placa limpa e funcional  
- 🌫️ **Dusty** — Placa suja  
- 🐦 **Bird Drop** — Dejetos de pássaros  
- ⚡ **Electrical Damage** — Danos elétricos  
- 🔧 **Physical Damage** — Danos físicos (rachaduras, quebras, etc)

Utilizamos o **Roboflow** para anotação, treinamento e exportação do modelo. Ele permite fácil integração via API, o que facilita o uso em aplicações reais.

---

## 🌱 Conexão com o GoCycle

Este projeto complementa o **GoCycle**, uma aplicação de aluguel de bicicletas elétricas que:

- Incentiva o uso de energia limpa  
- Recompensa os usuários com pontos a cada hora de uso  
- Usa placas solares para carregar os veículos  

O modelo de detecção entra como **suporte à manutenção do sistema**, ajudando a identificar placas danificadas e garantindo a eficiência da infraestrutura energética.

---

## 🔗 Links Importantes

- 🧠 **Modelo Roboflow**: [Solar Panel Detection](https://universe.roboflow.com/melissa-y6dfd/solar-panel-detection-bdmpc)  
