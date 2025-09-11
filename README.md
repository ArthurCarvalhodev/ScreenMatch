# ScreenMatch 🎬

# 🎬 Catálogo de Filmes e Séries (Java)

Este projeto é um sistema simples em **Java** para gerenciar e classificar **títulos** (filmes, séries e episódios).  
Ele foi desenvolvido com o objetivo de praticar **Programação Orientada a Objetos (POO)**, explorando conceitos como **herança, interfaces, polimorfismo e encapsulamento**.

---

## 📂 Estrutura do Projeto

O projeto é composto pelas seguintes classes:

- **`Titulo`** → Classe base que representa um título (nome, ano de lançamento, duração, avaliações, etc).
- **`Filme`** → Extende `Titulo`, adicionando características específicas de filmes.
- **`Serie`** → Extende `Titulo`, com informações de temporadas, episódios e cálculo de duração total.
- **`Episodio`** → Representa um episódio de série, podendo ser avaliado e recomendado.
- **`Classificavel`** → Interface para padronizar a forma de recomendação de títulos.
- **`FiltroRecomendacao`** → Classe responsável por filtrar títulos recomendados com base na avaliação.
- **`CalculadoraDeTempo`** → Calcula a soma da duração total de todos os títulos assistidos.
- **`Principal`** → Classe principal que executa o programa, criando instâncias e simulando o uso.

---

## ⚙️ Funcionalidades

- ✅ Cadastro de filmes, séries e episódios.  
- ✅ Sistema de avaliação e cálculo da média de notas.  
- ✅ Recomendações automáticas baseadas em avaliações.  
- ✅ Cálculo da duração total de títulos assistidos.  
- ✅ Uso de **interfaces** e **polimorfismo** para flexibilidade.  

---

## 🛠️ Tecnologias Utilizadas

- **Java 17+** (pode ser executado em versões anteriores também).  
- **Paradigma POO**: herança, abstração, polimorfismo e encapsulamento.  

---

📌 Aprendizados

Durante o desenvolvimento, foram aplicados conceitos fundamentais de POO em Java, como:

Encapsulamento de atributos e métodos.

Herança para especialização de classes (Filme e Serie).

Uso de interfaces (Classificavel) para padronização.

Polimorfismo aplicado em métodos de recomendação.

👨‍💻 Autor

Projeto desenvolvido por Arthur Carvalho como prática de Java e POO.
Se gostou, ⭐ marque este repositório e contribua! 🚀

