# Flappy Bird AI

**Flappy Bird AI** é um projeto que utiliza o modelo NEAT (NeuroEvolution of Augmenting Topologies) para treinar uma Inteligência Artificial a jogar o clássico jogo *Flappy Bird*. Este repositório faz parte de uma iniciativa maior e depende do [Flappy Bird Base](https://github.com/Canela-san/Flappy-Bird-Base) para o ambiente do jogo.

---

## Objetivos do Projeto
1. Demonstrar o uso de algoritmos evolutivos (NEAT) no treinamento de IA para jogos.
2. Criar uma integração clara entre o modelo de IA e o ambiente do jogo.
3. Servir como um recurso educacional para quem deseja aprender sobre aprendizado de máquina aplicado a jogos.

> **Nota:** Este projeto é público e de código aberto. Todos são bem-vindos para usar, modificar e contribuir.

---

## Estrutura do Projeto
O projeto está organizado para ser modular e facilitar a compreensão:

```
Flappy-Bird-AI/
├── src/                     # Código-fonte principal
│   ├── ai.py                # Implementação do modelo NEAT
│   ├── train.py             # Script principal para treinar a IA
│   ├── visualize.py         # Funções para visualizar o progresso do treinamento
│   └── utils.py             # Funções auxiliares
├── config/                  # Configurações do modelo NEAT
├── README.md                # Documentação do projeto
├── requirements.txt         # Dependências do projeto
└── assets/                  # Opcional: Recursos visuais e sons para o treinamento
```

---

## Requisitos
Certifique-se de ter o Python 3.8 ou superior instalado. As dependências do projeto estão listadas no arquivo `requirements.txt`. Para instalá-las, execute:

```bash
pip install -r requirements.txt
```

Além disso, é necessário clonar o repositório [Flappy Bird Base](https://github.com/Canela-san/Flappy-Bird-Base) e configurá-lo corretamente. Consulte o README do repositório base para instruções.

---

## Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/Canela-san/Flappy-Bird-AI.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd Flappy-Bird-AI
   ```
3. Configure o ambiente do jogo:
   - Certifique-se de que o repositório [Flappy Bird Base](https://github.com/Canela-san/Flappy-Bird-Base) está configurado e funcional.

4. Inicie o treinamento da IA:
   ```bash
   python src/train.py
   ```

5. Visualize o progresso:
   Durante o treinamento, gráficos e estatísticas podem ser gerados para ajudar a entender o desempenho da IA.

---

## Parte de um Projeto Maior
Este repositório faz parte de um projeto modular que inclui:
- **[Flappy Bird Base](https://github.com/Canela-san/Flappy-Bird-Base):** O jogo base em Python usando Pygame.
- **Flappy Bird AI:** A implementação da IA para treinar o agente a jogar o jogo.

---

## Contribuições
Contribuições são sempre bem-vindas! Siga as etapas abaixo para contribuir:
1. Faça um fork do repositório.
2. Crie uma nova branch para a sua funcionalidade ou correção:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça o commit das suas alterações:
   ```bash
   git commit -m "Minha nova funcionalidade"
   ```
4. Envie suas alterações:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---

## Licença
Este projeto está licenciado sob a [Licença MIT](LICENSE). Sinta-se à vontade para usá-lo, modificá-lo e distribuí-lo conforme necessário.

---

## Contato
Para dúvidas ou sugestões, entre em contato através do meu perfil no GitHub: [Canela-san](https://github.com/Canela-san).

---

**Divirta-se e acompanhe o progresso da IA!** 🤖🎮

