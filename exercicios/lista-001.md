# Lista de Exercícios 1

---

### 1 - Instalar o Docker em seu OS

---

### 2 - (Linux Apenas) Adicionar seu usuário ao grupo do docker, para não precisar rodar com sudo

---

### 3 - Brincar na Docker Store, encontrar imagens e rodar alguns exemplos

---

### 4 - Sub-comando `volume`

#### 4.1 - Analisar a opções do comando `docker volume --help`

#### 4.2 - Listar, Criar, Remover e Inspecionar os volumes nomeados.

#### 4.3 - Remover todos os volumes que não estão conectados a um container, com 1 único container

---

### 5 - Sub-comando `image`

#### 5.1 - Listar, Baixar, Remover e inspecionar imagens com o comando `docker image`

#### 5.2 - Baixar pelo menos mais de 1 tag de uma imagem (exemplo: ubuntu:16.04 e ubuntu:17.04)

---

### 6 - Sub-comando `run`

#### 6.1 - Executar imagens docker baixadas anteriormente

#### 6.2 - Executar pelo menos 1 exemplo com mapeamento de portas (opção -p)

#### 6.3 - Executar pelo menos 1 exemplo com mapeamento de pastas (opção -v passando um caminho do host)

#### 6.4 - Executar pelo menos 1 exemplo com mapeamento de volume nomeado (opção -v, com volumes criados no item #4)

#### 6.5 - Executar independentemente, e em conjunto, uma imagem com as opções (`-i`, `-t` e `-it`)

#### 6.6 - Executar pelo menos 1 exemplo passando um comando customizado para inicializar o container (exemplo sh vs bash)

#### 6.7 - Executar 1 container, com a opção de auto remoção (`--rm`)

---

### 7 - Operações Básicas em Containers

#### 7.1 - Parar um container em execução com o commando `docker stop`

#### 7.2 - Parar um container em execução com o comando `docker kill`

#### 7.3 - Remover um container existente já parado

#### 7.4 - Remover um container que está em execução, a força

#### 7.5 - Listar os containers em execução.

#### 7.6 - Listar os containers existente, que não estão em execução.

#### 7.7 - Parar todos os containers em execução com 1 único comando

#### 7.8 - Remover todos os containers parados com 1 único comando

#### 7.9 - Remover todos os containers, parados ou em execução, com 1 comando

