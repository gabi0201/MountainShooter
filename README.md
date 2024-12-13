![alt text](https://github.com/borinvini/MountainShooter/blob/main/asset/Player1.png?raw=true "Mountain Shooter") Mountain Shooter ![alt text](https://github.com/borinvini/MountainShooter/blob/main/asset/Player1.png?raw=true "Mountain Shooter")
===============
 

### About

Mountain Shooter é um jogo arcade 2D desenvolvido com Pygame. Originalmente, o jogo tinha 2 níveis, cada um terminando com um evento de timeout. O jogo pode ser jogado no modo cooperativo (2 jogadores). O placar é salvo em um banco de dados (SQLite3).

Como parte de um trabalho acadêmico, o jogo foi **estendido para incluir um novo nível, o Level 3**, com novos cenários, inimigos e desafios.

### Repositório Original

Este projeto foi originalmente desenvolvido por [borinvini](https://github.com/borinvini/MountainShooter). Agradeço ao autor pela base do código, que foi utilizado e modificado para o desenvolvimento do novo nível.

### Alterações Realizadas

Este projeto foi modificado com as seguintes implementações:
- **Novo nível:** Level 3.
  - Cenários para o novo nível criados (Level3Bg).
  - Novo inimigo adicionado (Enemy3).
  - Integração do Level 3 no fluxo do jogo.
- Alterações realizadas em arquivos como:
  - `EntityFactory.py`: Adição de suporte para Level3Bg e Enemy3.
  - `Level.py`: Lógica para carregar o novo nível.
  - `Const.py`: Ajustes e inclusão de constantes relacionadas ao Level 3.

---

### Como Rodar o Jogo

1. Clone o repositório:
   ```bash
   git clone https://github.com/gabi0201/MountainShooter.git

2. Instale as dependências listadas em requirements.txt
    ```bash
   pip install -r requirements.txt

3. Execute o jogo
    ```bash
    python main.py



### MENU DO JOGO

![Menu](https://github.com/user-attachments/assets/c9524f59-6ebd-443a-82c0-53b63eb2128f)

GAME LEVEL 1

![Level1](https://github.com/user-attachments/assets/8af63514-178d-44c9-9eb0-299e0aee0933)


### Sinta-se à vontade para contribuir!