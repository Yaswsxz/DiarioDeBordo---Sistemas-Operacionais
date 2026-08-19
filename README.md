# HD (Hard Disk / Disco Rígido)

## Autoras

- Yasmin Fernanda de Carvalho
- Nívea Sofia

## O que é um HD

O HD, sigla para *Hard Disk* (Disco Rígido), é um dispositivo de armazenamento não volátil usado para guardar dados de forma permanente em computadores, servidores e outros equipamentos eletrônicos. Diferente da memória RAM, o conteúdo gravado em um HD não é perdido quando o equipamento é desligado.

## Como funciona

<div align="center">
    <img src="hdFoto.webp" alt="Componentes internos de um HD" width="500">
</div>

O HD armazena informações em pratos (discos) metálicos recobertos por material magnético, que giram em alta velocidade dentro do gabinete do dispositivo. Uma cabeça de leitura e gravação, posicionada a poucos nanômetros da superfície dos pratos (sem tocá-la), se move para ler ou gravar dados em trilhas magnéticas concêntricas, que por sua vez são divididas em setores.

Os principais componentes de um HD são:

- **Pratos (discos):** superfícies magnéticas onde os dados são gravados, geralmente de alumínio ou vidro revestidos com uma camada magnética.
- **Cabeça de leitura/gravação:** lê e grava as informações magnéticas, "flutuando" sobre os pratos em um colchão de ar gerado pela própria rotação.
- **Motor de rotação (spindle motor):** gira os pratos em velocidades como 5.400, 7.200, 10.000 ou 15.000 RPM; quanto maior a rotação, mais rápido o acesso aos dados.
- **Braço atuador:** move a cabeça de leitura/gravação sobre os pratos, posicionando-a na trilha correta.
- **Placa controladora:** gerencia a comunicação entre o HD e o computador, controlando cache, comandos e correção de erros.

### Como os dados são gravados

A gravação é feita por meio de magnetismo: a cabeça altera a polaridade de pequenas regiões magnéticas no prato, representando bits 0 e 1. Tecnologias como **PMR (Perpendicular Magnetic Recording)** orientam essas partículas verticalmente, aumentando a densidade de dados. Modelos mais recentes usam **SMR (Shingled Magnetic Recording)**, que sobrepõe trilhas parcialmente para ganhar capacidade, e **HAMR/MAMR**, que usam calor ou micro-ondas para permitir gravações ainda mais densas.

## Tipos de HD

### 1. HDD (Hard Disk Drive)
É o modelo tradicional, mecânico, com partes móveis (pratos e cabeças). Características:

- Maior capacidade de armazenamento por custo (mais barato por GB).
- Velocidade de leitura/gravação mais baixa, limitada pela rotação física dos pratos.
- Mais suscetível a danos por impacto e vibração, por possuir partes móveis.
- Consome mais energia e gera mais ruído que um SSD.
- Subdivide-se em modelos **desktop** (3,5", maior capacidade), **notebook** (2,5", mais compactos) e **enterprise/NAS**, projetados para operação contínua 24/7 com maior durabilidade.

### 2. SSD (Solid State Drive)
Embora tecnicamente não seja um "HD" no sentido mecânico, é frequentemente comparado a ele por cumprir a mesma função de armazenamento. Diferenças principais:

- Utiliza memória flash NAND (chips), sem partes móveis.
- Velocidade de leitura/gravação muito superior, sem tempo de busca mecânico.
- Mais resistente a impactos.
- Custo por GB mais elevado que o HDD, embora essa diferença venha diminuindo.
- Menor consumo de energia e funcionamento silencioso.
- Existem variações internas como **SLC, MLC, TLC e QLC**, que definem quantos bits cada célula de memória armazena — quanto mais bits por célula, maior a capacidade, mas menor a durabilidade e velocidade.

### 3. HD Híbrido (SSHD)
Combina um HDD tradicional com uma pequena quantidade de memória flash (geralmente 8 GB a 32 GB), usada como cache para armazenar os dados acessados com mais frequência, melhorando o desempenho percebido sem elevar tanto o custo em relação a um SSD puro. É uma solução intermediária, hoje pouco utilizada frente à queda de preço dos SSDs.

### 4. HD Externo
Qualquer HDD ou SSD que se conecta ao computador por uma interface externa (geralmente USB, mas também Thunderbolt), usado para backup, transporte de arquivos ou expansão de armazenamento. Costuma ter case próprio com proteção e, em alguns casos, fonte de alimentação independente (modelos 3,5").

### 5. HD Interno
Instalado diretamente dentro do gabinete do computador, conectado via interfaces como SATA ou, no caso de SSDs mais modernos, NVMe (M.2). É a opção padrão para o armazenamento principal do sistema operacional e aplicativos.

### 6. HD de Servidor/Enterprise
Projetados para uso corporativo, com foco em confiabilidade e tempo de atividade contínuo. Costumam usar interface SAS, ter maior MTBF (tempo médio entre falhas) e suportar configurações em RAID para redundância de dados.

## Interfaces de conexão

- **IDE/PATA:** interface antiga, com cabos largos de 40 ou 80 vias, praticamente em desuso desde meados dos anos 2000.
- **SATA (Serial ATA):** padrão mais comum atualmente para HDDs e SSDs 2,5"/3,5", com versões SATA I, II e III (até 6 Gb/s).
- **SAS (Serial Attached SCSI):** usada principalmente em servidores, oferece maior confiabilidade e suporte a múltiplos dispositivos conectados em cadeia.
- **USB:** utilizada em HDs externos, com variações de velocidade conforme o padrão (USB 2.0, 3.0, 3.1, 3.2).
- **NVMe/M.2:** interface de alta velocidade usada por SSDs modernos, conectada diretamente ao barramento PCIe, alcançando velocidades muito superiores ao SATA.
- **Thunderbolt:** interface de alta performance, comum em HDs/SSDs externos voltados a edição de vídeo e uso profissional.

## Capacidade de armazenamento

Os HDs são medidos em unidades como:

- **GB (Gigabyte):** modelos mais antigos ou de baixa capacidade.
- **TB (Terabyte):** padrão atual para a maioria dos HDs, variando geralmente de 500 GB a 20 TB ou mais, dependendo do modelo e fabricante.

## Fator de forma (tamanho físico)

- **3,5 polegadas:** padrão em desktops e servidores, oferece maior capacidade de armazenamento.
- **2,5 polegadas:** padrão em notebooks e também usado em SSDs, mais compacto e com menor consumo de energia.
- **M.2:** formato pequeno tipo "pente", usado por SSDs NVMe e SATA, encaixado diretamente na placa-mãe sem cabos.

## Um breve histórico

O primeiro HD, o IBM 350, foi lançado em 1956 e pesava cerca de uma tonelada, armazenando apenas 5 MB de dados. Ao longo das décadas seguintes, a tecnologia evoluiu drasticamente: os discos ficaram menores, mais rápidos e com capacidades cada vez maiores, enquanto o custo por megabyte caiu exponencialmente. Já os SSDs começaram a se popularizar comercialmente a partir dos anos 2000 e ganharam força no mercado consumidor na década de 2010, à medida que o preço da memória flash foi caindo.

## Vantagens e desvantagens do HDD

**Vantagens:**
- Custo por GB mais baixo.
- Boa opção para armazenamento de grandes volumes de dados (backups, arquivos de mídia).
- Tecnologia madura e confiável para uso prolongado quando bem cuidada.

**Desvantagens:**
- Mais lento que SSDs.
- Mais vulnerável a quedas e impactos físicos.
- Maior consumo de energia e geração de calor.
- Ruído perceptível durante o funcionamento.

## Cuidados e manutenção

- Evitar movimentar o computador ou o HD externo enquanto está em uso.
- Manter o equipamento em local ventilado, evitando superaquecimento.
- Fazer backups periódicos, já que HDs mecânicos têm vida útil limitada e podem falhar.
- Utilizar estabilizadores ou no-breaks para evitar danos por oscilação de energia.
- Verificar periodicamente a saúde do disco com ferramentas como o SMART.

## Considerações finais

O HD continua sendo uma opção relevante quando o objetivo é armazenar grandes quantidades de dados a um custo menor, especialmente em backups e servidores de arquivos. Já os SSDs se tornaram o padrão para desempenho, sendo amplamente utilizados como unidade principal em notebooks e desktops modernos, muitas vezes em conjunto com um HDD para armazenamento secundário.

--- 

# Processo de Inicialização 

<div align="center">
    <img src="fluxograma.svg" alt="Componentes internos de um HD" width="1000">
</div>

## 1. Quais componentes de hardware são acionados em cada etapa

1. A **fonte** energiza a **placa-mãe**, que ativa o **processador (CPU)**.
2. A **CPU** aponta para um endereço fixo de memória onde está o **BIOS**, armazenado na **memória ROM** ou **memória EEPROM** (mais comum atualmente).
3. O **BIOS** busca por uma fonte de inicialização no armazenamento, que pode ser:
   - Disco rígido (**HDD/SSD**), via **SATA**
   - **Pendrive USB**
4. O **núcleo do SO (kernel)** é carregado na **memória RAM**.


## 2. Quais funções o BIOS/UEFI executa

- **Realiza o POST (Power-On Self Test)**, que verifica a integridade do hardware e dos periféricos, varrendo os barramentos PCIe e PCI.
- **Acessa o CMOS** (BIOS) **ou NVRAM** (UEFI) para buscar informações salvas anteriormente (data/hora, configurações de hardware).
- **Inicializa os controladores** (SATA, USB, PCIe), necessários para se comunicar com o armazenamento e demais dispositivos.
- Realiza a **busca pelo dispositivo de inicialização**.
- Fornece uma **interface de configuração** (Setup), permitindo, por exemplo, escolher outra fonte de inicialização (como um pendrive), entre outras configurações.
- **Aciona o gerenciador de inicialização (bootloader)**.

### UEFI vs. BIOS

| | BIOS (legado) | UEFI (moderno) |
|---|---|---|
| Onde busca o código de boot | **MBR** (Master Boot Record), no setor 0 do disco | Partição especial **ESP** (EFI System Partition), onde fica o arquivo `.efi` do bootloader |
| Memória de configurações | CMOS (volátil, depende de bateria) | NVRAM (não-volátil) |

## 3. Como o sistema operacional assume o controle

1. O **bootloader** carrega o **kernel** (núcleo do sistema operacional) na **memória RAM**.
2. O bootloader **transfere o controle da CPU** para o kernel.
3. O **kernel** assume e passa a ser responsável por:
   - Gerenciamento de memória
   - Gerenciamento de processos
   - Drivers de dispositivos
   - Chamadas de sistema e segurança
4. O kernel inicializa suas **tabelas** e o **sistema de arquivos**, carrega os **drivers** e o restante do sistema operacional, e então cria os **processos de segundo plano** necessários.

## 4. Onde entram os drivers e gerenciadores de recursos

Os drivers e gerenciadores de recursos entram na fase em que o **kernel assume o controle**:

- Para cada dispositivo, o kernel **confere se existe um driver disponível**.
- Em caso de ausência, o sistema pode sinalizar ao usuário (ex.: mensagem de "dispositivo desconhecido"), solicitando a instalação do driver correspondente.
- Assim que os drivers estão disponíveis, o sistema operacional os **carrega no núcleo**.

## 5. Papel dos barramentos e dispositivos de E/S nesse processo

Os barramentos aparecem em **três momentos distintos** do processo de boot:

1. **Durante a POST:** o BIOS/UEFI percorre fisicamente os barramentos (PCIe, PCI) para realizar o autoteste dos dispositivos conectados.
2. **Na busca pelo dispositivo de boot:** o barramento correspondente (SATA, USB) é usado para se comunicar com o armazenamento e localizar o setor/partição de boot.
3. **Quando o kernel assume o controle:** o kernel usa os drivers para se comunicar com os dispositivos através dos barramentos, de forma contínua durante toda a operação do sistema.

## Resumo da sequência completa

```
Fonte → Placa-mãe → CPU → BIOS/UEFI (ROM/EEPROM)
   → POST → CMOS/NVRAM → Controladores (SATA/USB/PCIe)
   → Busca do dispositivo de boot
   → [BIOS: MBR → VBR]  ou  [UEFI: ESP → arquivo .efi]
   → Bootloader → Kernel carregado na RAM
   → Kernel assume o controle → Drivers e gerenciadores de recursos
   → Processos de segundo plano → Tela de login / sistema pronto
```